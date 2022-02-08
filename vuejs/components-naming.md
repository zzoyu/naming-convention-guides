# VueJS 네이밍 컨벤션 > 컴포넌트 작명

## 파스칼 케이스
- 대문자로 시작합니다.
- 컴포넌트 이름은 반드시 "AlertModal", "DropdownMenu"나 "NavbarLogo"와 같이 단어의 조합이어야 합니다.
- 자식 컴포넌트는 부모 컴포넌트의 이름을 접두사로 사용해야 합니다. 예를 들어 AlertModal의 자식인 Form 컴포넌트는 AlertModalForm이 되어야 합니다.
- 약자나 축약어를 피합니다.


```javascript
export default {
  name: 'AlertModal'
}
```

