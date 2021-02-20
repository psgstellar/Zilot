# The Zilot Project

## An Analsis Project for Github Generalization

### 2021-02-20 Issue

#### Data

![Data](./assets/images/issue/today1.png)

![Data](./assets/images/issue/today2.png)

![Data](./assets/images/issue/today3.png)

#### Problems

![Problems](./assets/images/issue/api1.png)

![Problems](./assets/images/issue/api2.png)

#### Solutions

- Using Github API


### Gihub API

##### Public Repo

```shell
curl -H "Accept: application/vnd.github.v3+json" https://api.github.com/repos/{owner}/{repo}/commits
```

##### Private Repo

```shell
curl -u "user_name:user_token" -H "Accept: application/vnd.github.v3+json" https://api.github.com/repos/{owner}{repo}/commits
```