# VueJS 네이밍 컨벤션 > 함수 작명

## camelCase 카멜 케이스
- 소문자로 시작합니다.
- 동사인 편이 좋습니다. e.g. getName(), buy(), count()
- 이름에 여러 단어가 포함되는 경우, 소문자로 시작하되 뒤따르는 단어들은 대문자로 시작합니다. e.g. getXmlParser()

```javascript
export default {
  methods: {
    getName () {
      return 'Hello World'
    }
  }
}
```
