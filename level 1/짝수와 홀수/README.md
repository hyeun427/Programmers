# 짝수와 홀수

<br/>

## 문제 설명

정수 num이 짝수일 경우 "Even"을 반환하고 홀수인 경우 "Odd"를 반환하는 함수, solution을 완성해주세요.

## 제한사항

- num은 int 범위의 정수입니다.
- 0은 짝수입니다.

---

## 입출력 예

| num | return |
| :-- | :----: |
| 3   | "Odd"  |
| 4   | "Even" |

---

## 🐤 내 답안

<details>
<summary>코드 보기</summary>
<div markdown="1">

```js
function solution(num) {
  if (num % 2 === 0) {
    return "Even";
  } else {
    return "Odd";
  }
}
```

</div>
</details>

---

> 프로그래머스의 level1 문제입니다.<br />
> 코딩테스트 연습 -> 연습문제
