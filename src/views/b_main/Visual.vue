<template>
  <div class="ma_visual-wrap">
    <div class="inner">
      <!-- 왼쪽 -->
      <div class="mavistxt">
        <img src="/public/images/geen/maintxt.png" alt="텍스트이미지" />
        <!-- <button>예약하기</button> -->
      </div>
      <!-- 오른쪽 -->
      <div class="mavisimg">
        <!-- <img src="/public/images/ma/ma_visual/mavisual.gif" alt="ma-viusal" /> -->
        <img src="/public/images/gh/ma_visual/mavisual.gif" alt="ma-viusal" />
        <!-- 오디오 음악재생 -->
        <audio autoplay controls class="mavisaudio" loop>
          <!-- <source src="/public/music.mp3" /> -->
          <source src="/public/images/gh/music.mp3" />
        </audio>
      </div>
    </div>
    <div class="bb_inner">
      <!-- 이용절차 -->
      <div class="bb_container1">
        <!-- 타이틀 1-->
        <div class="bb_title1">
          <!-- 제목 -->
          <div class="title_txt1">
            <h1>짐운송 이용절차</h1>
          </div>
        </div>
        <!-- 아이콘설명 -->
        <div class="bb_orderProcess bb_plusMinar">
          <!-- 아이콘1 -->
          <div class="bb_processIcon1">
            <!-- 아이콘1_이미지 -->
            <div class="bb_processIcon1_img">
              <img src="/public/images/yr/page1/1p_icon1.png" alt="icon1" />
            </div>
            <!-- 아이콘1_글 -->
            <span class="bb_span">예약/결제</span>
          </div>
          <!-- 화살표 -->
          <div class="arrow">
            <img src="/public/images/yr/page1/arrow.png" alt="arrow1" />
          </div>
          <!-- 아이콘2 -->
          <div class="bb_processIcon1">
            <!-- 아이콘2_이미지 -->
            <div class="bb_processIcon1_img">
              <img src="/public/images/yr/page1/1p_icon2.png" alt="icon2" />
            </div>
            <!-- 아이콘2_글 -->
            <span class="bb_span">사진촬영/업로드</span>
          </div>
          <!-- 화살표 -->
          <div class="arrow">
            <img src="/public/images/yr/page1/arrow.png" alt="arrow1" />
          </div>
          <!-- 아이콘3 -->
          <div class="bb_processIcon1">
            <!-- 아이콘3_이미지 -->
            <div class="bb_processIcon1_img">
              <img src="/public/images/yr/page1/1p_icon3.png" alt="icon3" />
            </div>
            <!-- 아이콘3_글 -->
            <span class="bb_span">픽업/배송</span>
          </div>
          <!-- 화살표 -->
          <div class="arrow">
            <img src="/public/images/yr/page1/arrow.png" alt="arrow1" />
          </div>
          <!-- 아이콘4 -->
          <div class="bb_processIcon1">
            <!-- 아이콘4_이미지 -->
            <div class="bb_processIcon1_img">
              <img src="/public/images/yr/page1/1p_icon4.png" alt="icon4" />
            </div>
            <!-- 아이콘4_글 -->
            <span class="bb_span">짐찾기</span>
          </div>
        </div>

        <!-- 아이콘설명 / 모바일일때 블락 -->
        <div class="bb_orderProcess bb_plus">
          <!-- 아이콘1 -->
          <div class="bb_processIcon1">
            <!-- 아이콘1_이미지 -->
            <div class="bb_processIcon1_img">
              <img src="/public/images/yr/page2/2p_icon1.png" alt="icon1" />
            </div>
            <!-- 아이콘1_글 -->
            <span class="bb_spanPlus">1. 예약/결제</span>
          </div>
          <!-- 화살표 -->
          <div class="arrow">
            <img src="/public/images/yr/page1/arrow.png" alt="arrow1" />
          </div>
          <!-- 아이콘2 -->
          <div class="bb_processIcon1">
            <!-- 아이콘2_이미지 -->
            <div class="bb_processIcon1_img">
              <img src="/public/images/yr/page2/2p_icon2.png" alt="icon2" />
            </div>
            <!-- 아이콘2_글 -->
            <span class="bb_spanPlus">2. 사진촬영/업로드</span>
          </div>
          <!-- 화살표 -->
          <div class="arrow">
            <img src="/public/images/yr/page1/arrow.png" alt="arrow1" />
          </div>
          <!-- 아이콘3 -->
          <div class="bb_processIcon1">
            <!-- 아이콘3_이미지 -->
            <div class="bb_processIcon1_img">
              <img src="/public/images/yr/page2/2p_icon3.png" alt="icon3" />
            </div>
            <!-- 아이콘3_글 -->
            <span class="bb_spanPlus">3. 픽업/배송</span>
          </div>
          <!-- 화살표 -->
          <div class="arrow">
            <img src="/public/images/yr/page1/arrow.png" alt="arrow1" />
          </div>
          <!-- 아이콘4 -->
          <div class="bb_processIcon1">
            <!-- 아이콘4_이미지 -->
            <div class="bb_processIcon1_img">
              <img src="/public/images/yr/page2/2p_icon4.png" alt="icon4" />
            </div>
            <!-- 아이콘4_글 -->
            <span class="bb_spanPlus">4. 짐찾기</span>
          </div>
        </div>
        <!-- 예약하기 버튼 -->
        <button>예약하기</button>
      </div>
    </div>
  </div>
</template>
<script setup></script>
<style lang="scss" scoped>
@use "/src/assets/Variables" as *;
/* 전체영역 */
.ma_visual-wrap .inner {
  width: 100%;
  max-width: 1300px;
  margin-top: 50px;
  display: flex;
  justify-content: center;
  margin: auto;
  align-items: center;
  flex-direction: row-reverse;
  /* background-color: antiquewhite; */
}
/* 왼쪽 - 텍스트박스  */
.mavistxt {
  align-items: center;
  width: 25%;
  img {
    width: 100%;
  }
}
.ma_vis_h1 h1:first-child {
  font-size: 20px !important;
  line-height: 30px !important;
  /* text-align: center; */
}
.mavistxt > h4 {
  width: 300px;
  font-size: 16px;
  color: #5a5a5a;
  margin-bottom: 10px;
}
.mavistxt > h1,
.ma_vis_h1 h1 {
  font-size: 40px;
  color: #5a5a5a;
  line-height: 50px;
}
.ma_vis_h1 {
  display: flex;
  justify-content: right;
  gap: 10px;
}
/* 맡기세요! (문구- 블루) */
.mablue {
  width: 230px;
  color: #0066b3 !important;
  padding: 20px 0 !important;
}
button {
  position: relative;
  width: 145px;
  line-height: 60px;
  font-size: 19px;
  background: #0066b3;
  color: white;
  border: none;
  border-radius: $border-radius-L + $border-radius-s;

  cursor: pointer;
  transition: 0.3s;
  text-align: center;

  @media screen and (max-width: 970px) {
    margin: 20px 0 10px;
  }

  span {
    font-size: 21px;
    margin-left: 5px;
  }
}

button:hover {
  background: #042844;
}
/* 오른쪽 - gif이미지 */
.mavisimg {
  position: relative;
  width: 70%;
  /* min-width: 390px; */
}
.mavisimg > img {
  width: 100%;
}
audio {
  width: 100%;
  max-width: 100px; /* 적절한 크기로 제한 */
  height: 30px;
  background-color: #fff !important; /* 배경색 변경 */
  border-radius: 10px; /* 둥근 모서리 */
  position: absolute;
  bottom: 50px;
  right: 0px;
}
// 추가 내용
// 이너
.bb_inner {
  position: relative;
  max-width: 1300px;
  margin: 50px auto;
  // background-color: beige;

  // 컨테이너1
  .bb_container1 {
    position: relative;
    width: 100%;
    // background-color: bisque;
    text-align: center;
    // 타이틀
    .bb_title1 {
      display: flex;
      gap: 10px;
      line-height: 40px;
      flex-wrap: wrap; /* 넘치면 자동 줄바꿈 */
      align-items: center; /* 세로 중앙 정렬 */
      justify-content: center; /* 가로 중앙 정렬 */
      padding-bottom: 10px;
      .title_txt1 h1 {
        font-size: 35px;
        font-weight: bold;
      }
    }
    // 이용절차
    // 이용절차
    .bb_orderProcess {
      position: relative;
      // background-color: aqua;
      width: 100%;
      display: flex;
      padding-right: 4%;
      padding-left: 4%;
      justify-content: space-between;

      .bb_processIcon1 {
        display: flex;
        justify-content: center;
        align-items: center;
        text-align: center;
        position: relative;

        flex-direction: column;

        .bb_processIcon1_img {
          display: flex; // ★ 추가 필수
          justify-content: center; // 수평 가운데
          align-items: center; // 수직 가운데
          flex-direction: column;
          width: 70%;
          height: 70%; // 필요 시 명확히 지정
          text-align: center;

          img {
            width: 100%;
            height: auto; // 비율 유지
          }
        }
        .bb_span {
          font-size: 20px;
        }
        span.bb_spanPlus {
          font-size: 20px;
        }
      }

      .arrow {
        position: relative;
        padding: 60px 0 80px 0;
      }

      .bb_kakao {
        display: flex;
        background-color: #f4f4f4;
        border-radius: 80px;
        width: 45%;
        position: relative;
        margin-top: 20px;
        cursor: pointer;
        .bb_kakaoIcon {
          padding: 3px;

          img {
            border-radius: 50px;
            width: 30px;
            height: 30px;
          }
        }
      }
    }
    .bb_plus {
      display: none;
    }
  }
} // 모바일 : 390px
@media screen and (max-width: 390px) {
  .mavisimg {
    margin-left: 10px;
  }
  .bb_inner {
    margin-top: 30px;
  }
  // 컨테이너1
  .bb_span {
    font-size: 15px !important;
  }
  .title_txt1 h1 {
    font-size: 25px !important;
  }
  .bb_title1 {
    padding-bottom: 20px !important;
  }

  .arrow {
    display: none;
  }
  .bb_plusMinar {
    display: none !important;
  }
  .bb_orderProcess {
    width: 80% !important;
    margin: auto;
    padding: 0 !important;
  }
  .bb_orderProcess.bb_plus {
    display: flex !important;
    justify-content: space-evenly !important;
    flex-wrap: wrap;
    gap: 10px; /* 간격 */
  }

  .bb_processIcon1 {
    width: 40%;
    justify-content: space-around !important;
    flex-wrap: wrap;
  }
  .bb_plus {
    display: block !important;
  }
  .bb_plus span {
    font-size: 15px !important;
  }

  .mavistxt {
    display: none !important;
  }

  button {
    margin-top: 40px;
  }
  audio {
    bottom: 0px;
    right: 0px;
  }
}
</style>
