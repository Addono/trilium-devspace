# Trilium DevSpace
## 📝 Table of Contents
- [About](#about)
- [Deployment](#deployment)
- [Usage](#usage)
- [Built Using](#built_using)
- [Authors](#authors)

## 🧐 About <a name = "about"></a>
Offers a simple method of deploying [Trilium](https://github.com/zadam/trilium) onto Kubernetes using DevSpace.

## 🚀 Deployment <a name = "deployment"></a>

### Prerequisites
Install [DevSpace](https://devspace.sh/), other installations than NPM are available as well and covered in their [documentation](https://devspace.sh/cli/docs/getting-started/installation):
```bash
npm install -g devspace
```

### Configuration
Open `devspace.yaml` and configure the hostname which you will be using for the deployment.

If you do not have a Kubernetes cluster setup yet, you can use the free tier from DevSpace Cloud. First, login into DevSpace Cloud:

```bash
devspace login
```

Then create the “space” to deploy the application in:
```bash
devspace create space trilium
```

### Deploying
You can kick-off the deployment by running:
```bash
devspace deploy
```

## ⛏️ Built Using <a name = "built_using"></a>
- [DevSpace](https://devspace.sh/)

## ✍️ Authors <a name = "authors"></a>
- [Adriaan Knapen](https://aknapen.nl) [![Addono@Gitlab](https://img.shields.io/badge/Gitlab-@Addono-orange?style=for-the-badge&logo=gitlab)](https://gitlab.com/Addono) [![Addono@Github](https://img.shields.io/badge/Github-@Addono-black?style=for-the-badge&logo=github)](https://github.com/Addono)
