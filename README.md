## 샘플 **프로젝트 설명**

1. NSTextAttachment 를 상속하고 emojiName,Type 변수를 추가한 커스텀 클래스를 만든다.
2. emojiName과 type(gif 혹은 lottie)를 설정한 후 attribute string 에 붙인다
3. Textview 의 attributeText 속성에 위에서 만든 텍스트를 넣어준다.
4. Textview 를 전체적으로 스캔하며 커스텀 attachment 가 붙어있는 위치에 로티 애니메이션 혹은 gif 이미지뷰를 추가한다. 

---

## 단점

텍스트뷰를 스캔할때마다 모든 로티/gif 서브뷰를 전부 삭제한 후 다시그려야함.

## Example

![ezgif.com-gif-maker (4).gif](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/feaf56cd-46bc-4106-9cb1-19057767998a/ezgif.com-gif-maker_(4).gif)
  
    
