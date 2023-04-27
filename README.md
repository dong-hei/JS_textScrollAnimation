# JS_텍스트스크롤애니메이션

 function initTexts(element, textArray) {
        textArray.push(...textArray)
        for (let i = 0; i < textArray.length; i++) {
          element.innerText += `${textArray[i]}\u00A0\u00A0\u00A0\u00A0`
        }
      }
      배열을 똑같은 내용 푸시해준다음 띄어쓰기 4번처리해준다음 P태그 안에 넣어준다.

  
