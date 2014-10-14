<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8">
  <title>JS Bin</title>
  <style>

  </style>
</head>
<body>
  <div class="page">
    <h1>중간고사</h1>
    <h2>인라인 요소 목록</h2>
    <p>다음은 HTML에서 자주 사용되는 요소들입니다.</p>
    <ul>
  <li><span>a</span> :하이퍼링크 (Anchor)</li>
  <li><span>img</span> : 이미지 (image)</li>
  <li><span>span</span> : 일반용도의 인라인 (Span)</li>
  <li><span>strong</span> : 중요 (Strong)</li>
  <li><span>em</span> : 강조 (Emphasis)</li>
</ul>
    <h2>CSS란?</h2>
      <p>CSS는 Casading Stylesheet의 약자이며 HTML 같은 마크업 언어로 작성된 문서를 꾸미기 위해 사용합니다. HTML 문서의 head 요고 안에 style 요소를 넣고 CSS 코드를 적으면 해당 문서를 다양하게 꾸밀 수 있습니다.<p>
      <P>CSS에 대한 더 자세한 설명은 <a href="#">CSS</a>문서를 참고하세요.</p>
  <h2>블럭 요소 목록</h2>
  <p>다음은 HTML에서 자주 사용되는 요소들입니다.</p>
  <ol>
  <li><span>p</span> :단락 (Paragraph)</li>
  <li><span>h1</span> : 큰제목 (Heading 1)</li>
  <li><span>ul</span> : 순서 없는 목록 (UnOrdered List)</li>
  <li><span>ol</span> : 순서 있는 목록 (Ordered List)</li>
  <li><span>table</span> : 표 (Table)</li>
</ol>
  <h2>표 만들기</h2>
  <p>표를 만들려면 table요소를 사용합니다.</p>
   <table>
    <thead>
    <tr>
      <th>음료</th>
      <th>가격</th>
      <th>알콜</th>
    </tr>
    </thead>
    <tbody>
    <tr>
      <td>아메리카노</td>
      <td>2,000</td>
      <td>X</td>
      </tr>
          <tr>
      <td>카페모카</td>
      <td>2,500</td>
      <td>X</td>
      </tr>
          <tr>
      <td>맥주</td>
      <td>3,000</td>
      <td>Y</td>
      </tr>
    </tbody>
  </table>
  <h2>HTML이란?</h2>
  <p>HYML은 하이퍼텍스트 마크업 언어 (Hypertext Markup Language)의 약자로, 웹 페이지를 만들 때 사용되는 문서 형식입니다.</p>
  <p>하이퍼텍스트(Hypertext)란 하이퍼링크(Hyperlink)를 담고 있는 문서를 뜻합니다. 하이퍼링크는 문서들이 서로 연결되어있는 고리를 말합니다.</p>
  <h2>중첩된 목록</h2>
  <p>목록 요소 안에 또다른 목록 요소를 중첩하여 사용할 수 있습니다.</p>
 
  <nav>
  <ol>
    <li>
  <div class="entery"> <span class="title">홍길동</span> </div>
<ol>
 <li>
         <div class="entery"> <span class="title">지각 없음</span> </div>
        </li>
    <li>
         <div class="entery"> <span class="title">결석 없음</span> </div>
      </li>
    <li>
         <div class="entery"> <span class="title">과제 만점</span> </div>
           </li>
    </ol> 
    <li>
  <div class="entery"> <span class="title">이몽룡</span> </div>
    <ol>
    </li>
      <li>
         <div class="entery"> <span class="title">지각 2회</span> </div>
        </li>
    <li>
         <div class="entery"> <span class="title">결석 없음</span> </div>
      </li>
    <li>
         <div class="entery"> <span class="title">과제 만점</span> </div>
           </li>
    </ol>
    </ol>
    </nav>
  <span><em>2014년 10월 14일 중간고사, 이한빈 작성</em></span>
  </div>
</body>
</html>
