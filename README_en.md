<h1 align="center">Title</h1>
<p align="center"><b>Introduce</b></p>

<p align="center">

  <a href="https://github.com/misitebao/yakia/blob/main/LICENSE">
    <img alt="GitHub" src="https://img.shields.io/github/license/misitebao/yakia"/>
  </a>
  <a href="https://github.com/misitebao/yakia/blob/main/LICENSE">
    <img alt="#contributors-" src="https://img.shields.io/badge/all_contributors-2-orange.svg?style=flat-square"/>
  </a>
  <img height="20" src="https://img.shields.io/badge/vuejs-%2335495e.svg?style=for-the-badge&logo=vuedotjs&logoColor=%234FC08D" alt="VueJs" />
  <img height="20" src="https://img.shields.io/badge/vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white" alt="Vite" />
  <img height="20" src="https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="TailwindCSS" />
  <img height="20" src="https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
  <img height="20" src="https://img.shields.io/badge/spring-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white" alt="Spring" />
  <img height="20" src="https://img.shields.io/badge/nestjs-%23E0234E.svg?style=for-the-badge&logo=nestjs&logoColor=white" alt="NestJS" />
  <img height="20" src="https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  <br/>

</p>

<div align="center">
<strong>
<samp>

English · [简体中文](README.md)

</samp>
</strong>
</div>

## Tbale of Content

[toc]

## QuickStart

### Install

```bash
# clone the repo
git clone `repo`

# install dependency
npm install

# run serve
npm run start

# build and deploy
npm run build
```

Directory description:

```
├─ config
├─ public
├─ scripts
├─ src
│  ├─ assets
│  ├─ elements    //存放所有 custom elements
│  ├─ store       //存放所有页面的 store
│  ├─ admin.js    //入口文件，会 build 成  admin.html
│  └─ index.js    //入口文件，会 build 成  index.html
```

### Usage

```jsx
import { forwardRef, useRef, useImperativeHandle } from 'react';

const MyInput = forwardRef(function MyInput(props, ref) {
  const inputRef = useRef(null);

  useImperativeHandle(ref, () => {
    return {
      focus() {
        inputRef.current.focus();
      },
      scrollIntoView() {
        inputRef.current.scrollIntoView();
      },
    };
  }, []);

  return <input {...props} ref={inputRef} />;
});
</script>
```

[→ 查看 demo](www.google.com)

## Contribution

<table>
    <tbody>
        <tr>
            <td>
                <a target="_blank" href="https://github.com/lalalavard"><img width="60px" src="https://avatars.githubusercontent.com/u/48318812?v=4"></a>
            </td>
            <td>
                <a target="_blank" href="https://github.com/kwobi "><img width="60px" src="https://avatars.githubusercontent.com/u/116106043?v=4"></a>
            </td>
        </tr>
    </tbody>
</table>

## Maintainers

- [kwobi](https://github.com/kwobi)
- [lavard](https://github.com/lalalavard)

## Thanks

- [people](www.google.com)

## License

- [MIT](https://opensource.org/licenses/MIT)
