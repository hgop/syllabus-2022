# Week 1 Assignment

**Turn in your GitHub repository URLs into Canvas solo or in pairs (please add `kthorri` and `fanneyyy` as collaborators)**

repository:

```text
.
├── .circleci
│   └── config.yml
├── assignments
│   ├── day01
│   │   └── answers.md
│   └── day02
│       └── answers.md
├── Justfile
├── README.md
├── scripts
│   ├── ci
│   │   └── yaml
│   │       └── merge.sh
│   └── verify_local_dev_environment.sh
└── src
    ├── connect4-client    
    │   ├── .dockerignore
    │   ├── .eslintrc.json
    │   ├── .gitignore
    │   ├── Dockerfile
    │   ├── k8s
    │   │   ├── deployment.template.yaml
    │   │   ├── ingress.template.yaml
    │   │   └── service.template.yaml
    │   ├── next.config.js
    │   ├── package.json
    │   ├── pages
    │   │   ├── api
    │   │   │   └── hello.ts
    │   │   ├── _app.tsx
    │   │   └── index.tsx
    │   ├── public
    │   │   ├── favicon.ico
    │   │   └── vercel.svg
    │   ├── README.md
    │   ├── styles
    │   │   ├── globals.css
    │   │   └── Home.module.css
    │   ├── tsconfig.json
    │   └── yarn.lock
    └── httpbin
        └── k8s
            ├── deployment.template.yaml
            ├── ingress.template.yaml
            └── service.template.yaml
```

Add a `./README.md` file, it should include the URL to the instance running
the game client `connect4.{{team-name}}.hgopteam.com`.

If you did anything extra, you should list it up in the `./README.md` if you
want us to take it into account.


Furthermore, please include links to issues that you participated in for bonuses.
