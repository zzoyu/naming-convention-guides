# VueJS 네이밍 컨벤션 > 템플릿 컴포넌트 작명

## PascalCase 파스칼 케이스
- 단일 파일 컴포넌트, 문자열 템플릿, JSX에서 사용합니다.
- 자체 닫기(self closing)를 해야 합니다.
- For example <HelloWorld/>, <ShareButton/>

## kebab-case 케밥 케이스
- DOM 템플릿에서 사용합니다.
- 자체 닫기(self closing)를 해서는 안 됩니다.
- For example <hello-world></hello-world>, <share-button></share-button>

```html
<template>
  <div>
    <HelloWorld/>
    <share-button></share-button>
  </div>
</template>
```