# revshells
<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
[![All Contributors](https://img.shields.io/badge/all_contributors-14-black.svg?style=flat-square)](#contributors-)
<!-- ALL-CONTRIBUTORS-BADGE:END -->
Hosted Reverse Shell generator with a ton of functionality -- (great for CTFs)
<br> [![Netlify Status](https://api.netlify.com/api/v1/badges/46dbabe0-23b7-42e6-b04b-e1769dc455ce/deploy-status)](https://app.netlify.com/sites/brave-swartz-5dcdab/deploys)

### Features

- Generate common listeners and reverse shells
- Raw mode to cURL shells to your machine.
- Button to increment the listening port number by 1
- URI and Base64 encoding
- LocalStorage to persist your configuration
- Dark and Light Modes

### Screenshot

![image](https://user-images.githubusercontent.com/44453666/111888563-02430f80-89b4-11eb-9e17-ea3de014cf69.png)

## Dev

It's recommended to use the netlify dev command if you're wanting to modify any of the server functions, such as for raw link support:

```
npx netlify dev
```

## Using Docker
Simply run the following commands within this repository to spin up the instance locally using a Docker container

```
docker build -t reverse_shell_generator .

docker run -d -p 80:80 reverse_shell_generator
```

Browse to http://localhost:80

## Contributors ✨

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
</a></td>
    <td align="center"><a href="https://skerritt.blog"><img src="https://avatars.githubusercontent.com/u/10378052?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Brandon</b></sub></a><br /><a href="https://github.com/0dayCTF/reverse-shell-generator/commits?author=bee-san" title="Code">💻</a></td>
    <td align="center"><a href="https://robiot.github.io/"><img src="https://avatars.githubusercontent.com/u/68228472?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Robiot</b></sub></a><br /><a href="#content-robiot" title="Content">🖋</a> <a href="#maintenance-robiot" title="Maintenance">🚧</a></td>
    <td align="center"><a href="https://github.com/Hydragyrum"><img src="https://avatars.githubusercontent.com/u/4928181?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Adam Bertrand</b></sub></a><br /><a href="#content-Hydragyrum" title="Content">🖋</a></td>
  </tr>
</table>

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->
