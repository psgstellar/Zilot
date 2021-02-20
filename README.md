# The Zilot Project

## An Analsis Project for Github Generalization

### 2021-02-20 Issue

#### Data

![Data](https://raw.githubusercontent.com/psgstellar/Zilot/analysis/assets/images/issue/today1.PNG)

![Data](https://raw.githubusercontent.com/psgstellar/Zilot/analysis/assets/images/issue/today1.PNG)

![Data](https://raw.githubusercontent.com/psgstellar/Zilot/analysis/assets/images/issue/today3.PNG)

#### Problems

![Problems](https://raw.githubusercontent.com/psgstellar/Zilot/analysis/assets/images/issue/api1.PNG)

![Problems](https://raw.githubusercontent.com/psgstellar/Zilot/analysis/assets/images/issue/api2.PNG)

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