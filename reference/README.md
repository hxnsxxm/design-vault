# Reference Box

## [box01](box01.html)

<div class="container">
  <div class="ref-container">
      <p class="ref-title">Reference</p>
      <ul class="ref-list">
          <li class="ref-item">
              <span>1</span> <a href="#">link</a>
          </li>
          <li class="ref-item">
              <span>2</span> <a href="#">link</a>
          </li>
          <li class="ref-item">
              <span>3</span> <a href="#">link</a>
          </li>
          <li class="ref-item">
              <span>4</span> <a href="#">link</a>
          </li>
          <li class="ref-item">
              <span>5</span> <a href="#">link</a>
          </li>
          <li class="ref-item">
              <span>6</span> <a href="#">link</a>
          </li>
          <li class="ref-item">
              <span>7</span> <a href="#">link</a>
          </li>
          <li class="ref-item">
              <span>8</span> <a href="#">link</a>
          </li>
          <li class="ref-item">
              <span>9</span> <a href="#">link</a>
          </li>
          <li class="ref-item">
              <span>10</span> <a href="#">linklinklinklinklinklinklinklinklinlinklinklinklinklinklinklinklinlinklinklinklinklinklinklinklinlinklinklinklinklinklinklinklinklinklinklinklinklinklinklinklink</a>
          </li>
          <li class="ref-item">
              <span>11</span> <a href="#">link</a>
          </li>
      </ul>
  </div>
</div>

<style>
  .ref-container {
      width: 100% !important;
      box-shadow: 0 5px 25px rgb(0 0 0 / 10%) !important;
  }

  .ref-container .ref-title,
  .ref-container .ref-list .ref-item span {
      background-color: rgb(255, 85, 68, 0.4) !important;
  }

  .ref-container .ref-title {
      font-size: 1.1rem !important;
      padding: 8px 20px 4px 16px !important;
      margin: 0 !important;
      line-height: 30px !important;
      color: #fff !important;
      border-top-left-radius: 10px !important;
      border-top-right-radius: 10px !important;
  }

  .ref-container .ref-title::before {
      content: '\f865' !important;
      font-family: 'Font Awesome 5 Pro' !important;
      margin-right: 10px !important;
      font-size: 1rem !important;
      font-weight: 400 !important;
      position: relative !important;
      top: -1px !important;
  }

  .ref-container .ref-list {
      list-style-type: none !important;
      padding: 0 !important;
      margin: 0 0 10px 0 !important;
      font-size: 1rem !important;
      border-bottom: 8px solid rgb(255, 85, 68, 0.4) !important;
      border-bottom-left-radius: 10px !important;
      border-bottom-right-radius: 10px !important;
  }

  .ref-container .ref-list .ref-item {
      padding: 6px 15px !important;
      border-bottom: 1px dashed #f0f0f0 !important;
      display: flex !important;
      align-items: center !important;
      gap: 0;
  }

  .ref-container .ref-list .ref-item:hover {
      background-color: rgb(255, 85, 68) !important;
  }

  .ref-container .ref-list .ref-item:hover a {
      color: #fff !important;
  }

  .ref-container .ref-list .ref-item:hover span {
      background-color: #fff !important;
      color: rgb(255, 85, 68) !important;
  }

  .ref-container .ref-list .ref-item span {
      display: inline-block !important;
      width: 20px !important;
      height: 20px !important;
      margin-right: 12px !important;
      font-weight: 600 !important;
      border-radius: 50% !important;
      text-align: center !important;
      line-height: 21px !important;
      color: #fff !important;
  }

  .ref-container .ref-list .ref-item a {
      width: calc(100% - 40px) !important;
      display: inline-block !important;
      text-decoration: none !important;
      color: rgb(70, 70, 70) !important;
      overflow-wrap: break-word !important;
  }

  .ref-container .ref-list .ref-item a::before {
      content: '\f0c1' !important;
      font-family: 'Font Awesome 5 Pro' !important;
      margin-left: 5px !important;
      margin-right: 10px !important;
      font-size: 0.6rem !important;
      position: relative !important;
      top: -2px !important;
  }
</style>
<link id="fa_pro" rel="stylesheet"
  href="https://tistory1.daumcdn.net/tistory/4939852/skin/images/fontAwesomePro5.css?_version_=1715313873"
  media="all" onload="this.media='all'">

<br><br>

# 앞으로 할 일

급함<br>


<br>
평범<br>

- [ ] [!important 속성 줄이기](#!important-속성-줄이기)

<br>
그닥<br>

- [ ] [span 태그로 숫자 감싸기](#span-태그로-숫자-감싸기)

<br><br>

# 상세

## span 태그로 숫자 감싸기
<br>
현재 span 태그로 숫자를 감싸기 위해서 HTML 편집기를 직접 수정한다.
이를 "숫자 링크"라고 입력했을 때 자동으로 span 태그로 감싸주는 기능을 추가한다.
<br>
<br>
중요도는 떨어짐 >> "서식"을 통해 미리 번호를 크게 만들어둘 수 있음.


<br>
<br>

## !important 속성 줄이기
<br>
현재 프로젝트에서 원하는 스타일 설정이 적용되지 않아, !important 속성을 사용하는 경우가 많다.  
이를 줄이기 위해서 !important 속성을 하나씩 줄여나간다.