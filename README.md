"# alita_demo" 
新建页面
alita g pages home

{
  "name": "umi-now",
  "version": 2,
  "env": {
    "NOW_ZEIT_ENV": "true"
  },
  "builds": [
    {
      "use": "@now/node",
      "config": {
        "includeFiles": [
          "dist/**/*"
        ]
      }
    }
  ]
}
