# Mobi FrameWork 사용 가이드
# 1️⃣ 제목 (Headers)
# 대제목 (H1)
## 중제목 (H2)
### 소제목 (H3)
#### H4
##### H5
###### H6

# 2️⃣ 텍스트 강조
**굵게**   -> **굵게**
*기울임*   -> *기울임*
~~취소선~~ -> ~~취소선~~

# 3️⃣ 목록
(1) 순서 없는 목록 (Unordered list)
- 항목 1
- 항목 2
  - 하위 항목 2-1
* 항목 3

(2) 순서 있는 목록 (Ordered list)
1. 첫 번째
2. 두 번째
   1. 하위 항목
3. 세 번째

# 4️⃣ 링크 & 이미지
[GitHub](https://github.com)        # 링크
![Alt Text](image_url)              # 이미지


로컬 이미지: ![Alt Text](./images/pic.png)

# 5️⃣ 코드
(1) 인라인 코드
사용법: `mvn clean install`

(2) 블록 코드 (Syntax Highlighting)
```java
public static void main(String[] args) {
    System.out.println("Hello, GitHub!");
}
```

> ```java ``` : 언어 지정하면 GitHub에서 하이라이팅

---

## 6️⃣ 인용문

```markdown
> 여기는 인용문입니다.
> 여러 줄도 가능합니다.

7️⃣ 표 (Tables)
| 항목 | 설명       |
|------|-----------|
| 이름 | GitHub    |
| 타입 | Markdown  |

8️⃣ 체크리스트
- [x] 완료된 항목
- [ ] 진행 중
- [ ] 미완료

9️⃣ 수평선
---
