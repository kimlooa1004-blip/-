[과제3.html](https://github.com/user-attachments/files/32844823/3.html)
<!DOCTYPE html>
<html>
  <head>
    <title>내 첫 웹페이지</title>
    <style>
      /* 제목 — 색상과 글꼴 크기 */
      h1 {
        color: #1a9aa8;
        font-size: 40px;
      }

      /* 본문 — padding과 배경색으로 카드처럼 */
      .card {
        padding: 24px;
        background-color: #f2f6f8;
        border-radius: 10px;
      }

      /* 좋아하는 것 — Flexbox 가로 정렬 */
      .container {
        display: flex;
        justify-content: center;
        gap: 12px;
      }

      .container div {
        background-color: #1a9aa8;
        color: white;
        padding: 16px 24px;
        border-radius: 8px;
      }
    </style>
  </head>
  <body>
    <h1>안녕하세요!</h1>

    <div class="card">
      <p class="intro">소개 문단입니다. 2601922빅데이터과입니다.</p>
    </div>

    <h2>좋아하는 것</h2>
    <div class="container">
      <div>강아지</div>
      <div>영화</div>
      <div>고양이</div>
    </div>
  </body>
</html>
