# JS_텍스트스크롤애니메이션

 function initTexts(element, textArray) {
        textArray.push(...textArray)
        for (let i = 0; i < textArray.length; i++) {
          element.innerText += `${textArray[i]}\u00A0\u00A0\u00A0\u00A0`
        }
      }
      배열을 똑같은 내용 푸시해준다음 띄어쓰기 4번처리해준다음 P태그 안에 넣어준다.

   count1++
        count2++
        count3++
        count4++
        animate 재귀함수
        
        function scrollHandler() {
        count1 += 15
        count2 += 15
        count3 += 15
        count4 += 15
      }
      스크롤할때마다 값을 더한다
      
          if (count > element.scrollWidth / 2) {
          element.style.transform = `translate3d(0, 0, 0)`
          count = 0
        } //카운트가 엘리먼트 절반값이상이면 element도 원위치 
        
         element.style.transform = `translate3d(${direction * count}px, 0, 0)`
        //그게아니면 곱한만큼 이동시키고
        
        return count
        //return 시켜 다음 함수에 잔영
