# VueJS 네이밍 컨벤션 > 단일 인스턴스 컴포넌트 작명

단일 인스턴스 컴포넌트들은 View 당 한번만 사용되는 것을 의미합니다.
예를 들어 로고, 네비게이션 바, 사이드 메뉴가 될 수 있습니다.

## PascalCase 파스칼 케이스(The를 접두사로 사용)
- The로 시작합니다.
- 뷰 당 한번만 사용되어야 합니다.
- For example TheNavbar, TheFooter, TheSideMenu, TheLogo

```javascript
export default {
  name: 'TheFooter'
}
```