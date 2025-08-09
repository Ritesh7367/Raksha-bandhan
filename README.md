<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title> Set your 💖</title>
    <style>
        @import url("https://fonts.googleapis.com/css2?family=Lora&display=swap");
@import url("https://fonts.googleapis.com/css2?family=EB+Garamond&display=swap");
* {
  margin: 0;
  box-sizing: border-box;
}

.instruction,
.book {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
}

body {
  width: 100%;
  height: 100vh;
  min-width: 900px;
  min-height: 700px;
  background: linear-gradient(rgba(251, 92, 64, 0.518), rgb(11 15 19));
  position: relative;
}
#botao1 {
  background: rgb(0, 0, 0);
  color: white;
  padding: 10px;
  margin-top: 60px;
}
.motive {
  margin-left: 10%;
  padding-top: 20%;
  color: white;
  font-family: Arial, Helvetica, sans-serif;
}
.motive span {
  background: rgb(0, 255, 174);
  color: rgb(202, 33, 33);
}
.book {
  width: 847px;
  height: 654.5px;
  transform: translate(-50%, -50%) rotatex(10deg) rotatey(-10deg);
  transform-style: preserve-3d;
}

.page {
  width: 423.5px;
  height: 654.5px;
  background: #eee;
  position: absolute;
  top: 0;
  right: 0;
  transition: transform 1s;
}

.page:nth-child(1) {
  padding: 5% 4% 4% 5%;
  transform-origin: 0% 50%;
  transform: translatez(-1px);
  background: #585abe;
}

.left-side:nth-child(1) {
  transform: translatez(1px) rotatey(-180deg);
}

.page:nth-child(2) {
  padding: 5% 5% 4% 4%;
  transform-origin: 100% 50%;
  transform: translatez(-2px) scalex(-1) translatex(100%);
  background: #c684ab;
}

.left-side:nth-child(2) {
  transform: translatez(2px) scalex(-1) translatex(100%) rotatey(180deg);
}

.page:nth-child(3) {
  padding: 5% 4% 4% 5%;
  transform-origin: 0% 50%;
  transform: translatez(-3px);
  background: #f5f5f5;
}

.left-side:nth-child(3) {
  transform: translatez(3px) rotatey(-180deg);
}

.page:nth-child(4) {
  padding: 5% 5% 4% 4%;
  transform-origin: 100% 50%;
  transform: translatez(-4px) scalex(-1) translatex(100%);
  background: #f5f5f5;
}

.left-side:nth-child(4) {
  transform: translatez(4px) scalex(-1) translatex(100%) rotatey(180deg);
}

.page:nth-child(5) {
  padding: 5% 4% 4% 5%;
  transform-origin: 0% 50%;
  transform: translatez(-5px);
  background: #f5f5f5;
}

.left-side:nth-child(5) {
  transform: translatez(5px) rotatey(-180deg);
}

.page:nth-child(6) {
  padding: 5% 5% 4% 4%;
  transform-origin: 100% 50%;
  transform: translatez(-6px) scalex(-1) translatex(100%);
  background: #f5f5f5;
}

.left-side:nth-child(6) {
  transform: translatez(6px) scalex(-1) translatex(100%) rotatey(180deg);
}

.page:nth-child(7) {
  padding: 5% 4% 4% 5%;
  transform-origin: 0% 50%;
  transform: translatez(-7px);
  background: #f5f5f5;
}

.left-side:nth-child(7) {
  transform: translatez(7px) rotatey(-180deg);
}

.page:nth-child(8) {
  padding: 5% 5% 4% 4%;
  transform-origin: 100% 50%;
  transform: translatez(-8px) scalex(-1) translatex(100%);
  background: #f5f5f5;
}

.left-side:nth-child(8) {
  transform: translatez(8px) scalex(-1) translatex(100%) rotatey(180deg);
}

.page:nth-child(9) {
  padding: 5% 4% 4% 5%;
  transform-origin: 0% 50%;
  transform: translatez(-9px);
  background: #f5f5f5;
}

.left-side:nth-child(9) {
  transform: translatez(9px) rotatey(-180deg);
}

.page:nth-child(10) {
  padding: 5% 5% 4% 4%;
  transform-origin: 100% 50%;
  transform: translatez(-10px) scalex(-1) translatex(100%);
  background: #ccc;
}

.left-side:nth-child(10) {
  transform: translatez(10px) scalex(-1) translatex(100%) rotatey(180deg);
}

.page:nth-child(11) {
  padding: 5% 4% 4% 5%;
  transform-origin: 0% 50%;
  transform: translatez(-11px);
  background: #ccc;
}

.left-side:nth-child(11) {
  transform: translatez(11px) rotatey(-180deg);
}

.page:nth-child(12) {
  padding: 5% 5% 4% 4%;
  transform-origin: 100% 50%;
  transform: translatez(-12px) scalex(-1) translatex(100%);
  background: #ccc;
}

.left-side:nth-child(12) {
  transform: translatez(12px) scalex(-1) translatex(100%) rotatey(180deg);
}

.page:nth-child(13) {
  padding: 5% 4% 4% 5%;
  transform-origin: 0% 50%;
  transform: translatez(-13px);
  background: #ccc;
}

.left-side:nth-child(13) {
  transform: translatez(13px) rotatey(-180deg);
}

.page:nth-child(14) {
  padding: 5% 5% 4% 4%;
  transform-origin: 100% 50%;
  transform: translatez(-14px) scalex(-1) translatex(100%);
  background: #ccc;
}

.left-side:nth-child(14) {
  transform: translatez(14px) scalex(-1) translatex(100%) rotatey(180deg);
}

.page:nth-child(15) {
  padding: 5% 4% 4% 5%;
  transform-origin: 0% 50%;
  transform: translatez(-15px);
  background: #ccc;
}

.left-side:nth-child(15) {
  transform: translatez(15px) rotatey(-180deg);
}
::selection {
  color: rgb(0, 0, 0);
  background: rgb(26, 209, 75);
}
.page:nth-child(16) {
  padding: 5% 5% 4% 4%;
  transform-origin: 100% 50%;
  transform: translatez(-16px) scalex(-1) translatex(100%);
  background: #ccc;
}

.left-side:nth-child(16) {
  transform: translatez(16px) scalex(-1) translatex(100%) rotatey(180deg);
}

.page:nth-child(17) {
  padding: 5% 4% 4% 5%;
  transform-origin: 0% 50%;
  transform: translatez(-17px);
  background: #ccc;
}

.left-side:nth-child(17) {
  transform: translatez(17px) rotatey(-180deg);
}

.page:nth-child(18) {
  padding: 5% 5% 4% 4%;
  transform-origin: 100% 50%;
  transform: translatez(-18px) scalex(-1) translatex(100%);
  background: #ccc;
}

.left-side:nth-child(18) {
  transform: translatez(18px) scalex(-1) translatex(100%) rotatey(180deg);
}

.page:nth-child(19) {
  padding: 5% 4% 4% 5%;
  transform-origin: 0% 50%;
  transform: translatez(-19px);
  background: #ccc;
}

.left-side:nth-child(19) {
  transform: translatez(19px) rotatey(-180deg);
}

.page:nth-child(20) {
  padding: 5% 5% 4% 4%;
  transform-origin: 100% 50%;
  transform: translatez(-20px) scalex(-1) translatex(100%);
  background: #f5f5f5;
}

.left-side:nth-child(20) {
  transform: translatez(20px) scalex(-1) translatex(100%) rotatey(180deg);
}

.page:nth-child(21) {
  padding: 5% 4% 4% 5%;
  transform-origin: 0% 50%;
  transform: translatez(-21px);
  background: #f5f5f5;
}

.left-side:nth-child(21) {
  transform: translatez(21px) rotatey(-180deg);
}

.page:nth-child(22) {
  padding: 5% 5% 4% 4%;
  transform-origin: 100% 50%;
  transform: translatez(-22px) scalex(-1) translatex(100%);
  background: #f5f5f5;
}

.left-side:nth-child(22) {
  transform: translatez(22px) scalex(-1) translatex(100%) rotatey(180deg);
}

.page:nth-child(23) {
  padding: 5% 4% 4% 5%;
  transform-origin: 0% 50%;
  transform: translatez(-23px);
  background: #f5f5f5;
}

.left-side:nth-child(23) {
  transform: translatez(23px) rotatey(-180deg);
}

.page:nth-child(24) {
  padding: 5% 5% 4% 4%;
  transform-origin: 100% 50%;
  transform: translatez(-24px) scalex(-1) translatex(100%);
  background: #f5f5f5;
}

.left-side:nth-child(24) {
  transform: translatez(24px) scalex(-1) translatex(100%) rotatey(180deg);
}

.page:nth-child(25) {
  padding: 5% 4% 4% 5%;
  transform-origin: 0% 50%;
  transform: translatez(-25px);
  background: #f5f5f5;
}

.left-side:nth-child(25) {
  transform: translatez(25px) rotatey(-180deg);
}

.page:nth-child(26) {
  padding: 5% 5% 4% 4%;
  transform-origin: 100% 50%;
  transform: translatez(-26px) scalex(-1) translatex(100%);
  background: #f5f5f5;
}

.left-side:nth-child(26) {
  transform: translatez(26px) scalex(-1) translatex(100%) rotatey(180deg);
}

.page:nth-child(27) {
  padding: 5% 4% 4% 5%;
  transform-origin: 0% 50%;
  transform: translatez(-27px);
  background: #f5f5f5;
}

.left-side:nth-child(27) {
  transform: translatez(27px) rotatey(-180deg);
}

.page:nth-child(28) {
  padding: 5% 5% 4% 4%;
  transform-origin: 100% 50%;
  transform: translatez(-28px) scalex(-1) translatex(100%);
  background: #f5f5f5;
}

.left-side:nth-child(28) {
  transform: translatez(28px) scalex(-1) translatex(100%) rotatey(180deg);
}

.page:nth-child(29) {
  padding: 5% 4% 4% 5%;
  transform-origin: 0% 50%;
  transform: translatez(-29px);
  background: #f5f5f5;
}

.left-side:nth-child(29) {
  transform: translatez(29px) rotatey(-180deg);
}

.page:nth-child(30) {
  padding: 5% 5% 4% 4%;
  transform-origin: 100% 50%;
  transform: translatez(-30px) scalex(-1) translatex(100%);
  background: #ccc;
}

.left-side:nth-child(30) {
  transform: translatez(30px) scalex(-1) translatex(100%) rotatey(180deg);
}

.page:nth-child(31) {
  padding: 5% 4% 4% 5%;
  transform-origin: 0% 50%;
  transform: translatez(-31px);
  background: #ccc;
}

.left-side:nth-child(31) {
  transform: translatez(31px) rotatey(-180deg);
}

.page:nth-child(32) {
  padding: 5% 5% 4% 4%;
  transform-origin: 100% 50%;
  transform: translatez(-32px) scalex(-1) translatex(100%);
  background: #ccc;
}

.left-side:nth-child(32) {
  transform: translatez(32px) scalex(-1) translatex(100%) rotatey(180deg);
}

.page:nth-child(33) {
  padding: 5% 4% 4% 5%;
  transform-origin: 0% 50%;
  transform: translatez(-33px);
  background: #ccc;
}

.left-side:nth-child(33) {
  transform: translatez(33px) rotatey(-180deg);
}

.page:nth-child(34) {
  padding: 5% 5% 4% 4%;
  transform-origin: 100% 50%;
  transform: translatez(-34px) scalex(-1) translatex(100%);
  background: #ccc;
}

.left-side:nth-child(34) {
  transform: translatez(34px) scalex(-1) translatex(100%) rotatey(180deg);
}

.page:nth-child(35) {
  padding: 5% 4% 4% 5%;
  transform-origin: 0% 50%;
  transform: translatez(-35px);
  background: #ccc;
}

.left-side:nth-child(35) {
  transform: translatez(35px) rotatey(-180deg);
}

.page:nth-child(36) {
  padding: 5% 5% 4% 4%;
  transform-origin: 100% 50%;
  transform: translatez(-36px) scalex(-1) translatex(100%);
  background: #ccc;
}

.left-side:nth-child(36) {
  transform: translatez(36px) scalex(-1) translatex(100%) rotatey(180deg);
}

.page:nth-child(37) {
  padding: 5% 4% 4% 5%;
  transform-origin: 0% 50%;
  transform: translatez(-37px);
  background: #ccc;
}

.left-side:nth-child(37) {
  transform: translatez(37px) rotatey(-180deg);
}

.page:nth-child(38) {
  padding: 5% 5% 4% 4%;
  transform-origin: 100% 50%;
  transform: translatez(-38px) scalex(-1) translatex(100%);
  background: #ccc;
}

.left-side:nth-child(38) {
  transform: translatez(38px) scalex(-1) translatex(100%) rotatey(180deg);
}

.page:nth-child(39) {
  padding: 5% 4% 4% 5%;
  transform-origin: 0% 50%;
  transform: translatez(-39px);
  background: #ccc;
}

.left-side:nth-child(39) {
  transform: translatez(39px) rotatey(-180deg);
}

.page:nth-child(40) {
  padding: 5% 5% 4% 4%;
  transform-origin: 100% 50%;
  transform: translatez(-40px) scalex(-1) translatex(100%);
  background: #f5f5f5;
}

.left-side:nth-child(40) {
  transform: translatez(40px) scalex(-1) translatex(100%) rotatey(180deg);
}

.page:nth-child(41) {
  padding: 5% 4% 4% 5%;
  transform-origin: 0% 50%;
  transform: translatez(-41px);
  background: #f5f5f5;
}

.left-side:nth-child(41) {
  transform: translatez(41px) rotatey(-180deg);
}

.page:nth-child(42) {
  padding: 5% 5% 4% 4%;
  transform-origin: 100% 50%;
  transform: translatez(-42px) scalex(-1) translatex(100%);
  background: #f5f5f5;
}

.left-side:nth-child(42) {
  transform: translatez(42px) scalex(-1) translatex(100%) rotatey(180deg);
}

.page:nth-child(43) {
  padding: 5% 4% 4% 5%;
  transform-origin: 0% 50%;
  transform: translatez(-43px);
  background: #f5f5f5;
}

.left-side:nth-child(43) {
  transform: translatez(43px) rotatey(-180deg);
}

.page:nth-child(44) {
  padding: 5% 5% 4% 4%;
  transform-origin: 100% 50%;
  transform: translatez(-44px) scalex(-1) translatex(100%);
  background: #f5f5f5;
}

.left-side:nth-child(44) {
  transform: translatez(44px) scalex(-1) translatex(100%) rotatey(180deg);
}

.page:nth-child(45) {
  padding: 5% 4% 4% 5%;
  transform-origin: 0% 50%;
  transform: translatez(-45px);
  background: #f5f5f5;
}

.left-side:nth-child(45) {
  transform: translatez(45px) rotatey(-180deg);
}

.page:nth-child(46) {
  padding: 5% 5% 4% 4%;
  transform-origin: 100% 50%;
  transform: translatez(-46px) scalex(-1) translatex(100%);
  background: #f5f5f5;
}

.left-side:nth-child(46) {
  transform: translatez(46px) scalex(-1) translatex(100%) rotatey(180deg);
}

.page:nth-child(47) {
  padding: 5% 4% 4% 5%;
  transform-origin: 0% 50%;
  transform: translatez(-47px);
  background: #f5f5f5;
}

.left-side:nth-child(47) {
  transform: translatez(47px) rotatey(-180deg);
}

.page:nth-child(48) {
  padding: 5% 5% 4% 4%;
  transform-origin: 100% 50%;
  transform: translatez(-48px) scalex(-1) translatex(100%);
  background: #f5f5f5;
}

.left-side:nth-child(48) {
  transform: translatez(48px) scalex(-1) translatex(100%) rotatey(180deg);
}

.page:nth-child(49) {
  padding: 5% 4% 4% 5%;
  transform-origin: 0% 50%;
  transform: translatez(-49px);
  background: #f5f5f5;
}

.left-side:nth-child(49) {
  transform: translatez(49px) rotatey(-180deg);
}

.page:nth-child(50) {
  padding: 5% 5% 4% 4%;
  transform-origin: 100% 50%;
  transform: translatez(-50px) scalex(-1) translatex(100%);
  background: #ccc;
}

.left-side:nth-child(50) {
  transform: translatez(50px) scalex(-1) translatex(100%) rotatey(180deg);
}

.page:nth-child(51) {
  padding: 5% 4% 4% 5%;
  transform-origin: 0% 50%;
  transform: translatez(-51px);
  background: #ccc;
}

.left-side:nth-child(51) {
  transform: translatez(51px) rotatey(-180deg);
}

.page:nth-child(52) {
  padding: 5% 5% 4% 4%;
  transform-origin: 100% 50%;
  transform: translatez(-52px) scalex(-1) translatex(100%);
  background: #ccc;
}

.left-side:nth-child(52) {
  transform: translatez(52px) scalex(-1) translatex(100%) rotatey(180deg);
}

.page:nth-child(53) {
  padding: 5% 4% 4% 5%;
  transform-origin: 0% 50%;
  transform: translatez(-53px);
  background: #ccc;
}

.left-side:nth-child(53) {
  transform: translatez(53px) rotatey(-180deg);
}

.page:nth-child(54) {
  padding: 5% 5% 4% 4%;
  transform-origin: 100% 50%;
  transform: translatez(-54px) scalex(-1) translatex(100%);
  background: #ccc;
}

.left-side:nth-child(54) {
  transform: translatez(54px) scalex(-1) translatex(100%) rotatey(180deg);
}

.page:nth-child(55) {
  padding: 5% 4% 4% 5%;
  transform-origin: 0% 50%;
  transform: translatez(-55px);
  background: #ccc;
}

.left-side:nth-child(55) {
  transform: translatez(55px) rotatey(-180deg);
}

.page:nth-child(56) {
  padding: 5% 5% 4% 4%;
  transform-origin: 100% 50%;
  transform: translatez(-56px) scalex(-1) translatex(100%);
  background: #ccc;
}

.left-side:nth-child(56) {
  transform: translatez(56px) scalex(-1) translatex(100%) rotatey(180deg);
}

.page:nth-child(57) {
  padding: 5% 4% 4% 5%;
  transform-origin: 0% 50%;
  transform: translatez(-57px);
  background: #ccc;
}

.left-side:nth-child(57) {
  transform: translatez(57px) rotatey(-180deg);
}

.page:nth-child(58) {
  padding: 5% 5% 4% 4%;
  transform-origin: 100% 50%;
  transform: translatez(-58px) scalex(-1) translatex(100%);
  background: #ccc;
}

.left-side:nth-child(58) {
  transform: translatez(58px) scalex(-1) translatex(100%) rotatey(180deg);
}

.page:nth-child(59) {
  padding: 5% 4% 4% 5%;
  transform-origin: 0% 50%;
  transform: translatez(-59px);
  background: #ccc;
}

.left-side:nth-child(59) {
  transform: translatez(59px) rotatey(-180deg);
}

.page:nth-child(60) {
  padding: 5% 5% 4% 4%;
  transform-origin: 100% 50%;
  transform: translatez(-60px) scalex(-1) translatex(100%);
  background: #f5f5f5;
}

.left-side:nth-child(60) {
  transform: translatez(60px) scalex(-1) translatex(100%) rotatey(180deg);
}

.page:nth-child(61) {
  padding: 5% 4% 4% 5%;
  transform-origin: 0% 50%;
  transform: translatez(-61px);
  background: #f5f5f5;
}

.left-side:nth-child(61) {
  transform: translatez(61px) rotatey(-180deg);
}

.page:nth-child(62) {
  padding: 5% 5% 4% 4%;
  transform-origin: 100% 50%;
  transform: translatez(-62px) scalex(-1) translatex(100%);
  background: #f5f5f5;
}

.left-side:nth-child(62) {
  transform: translatez(62px) scalex(-1) translatex(100%) rotatey(180deg);
}

.page:nth-child(63) {
  padding: 5% 4% 4% 5%;
  transform-origin: 0% 50%;
  transform: translatez(-63px);
  background: #f5f5f5;
}

.left-side:nth-child(63) {
  transform: translatez(63px) rotatey(-180deg);
}

.page:nth-child(64) {
  padding: 5% 5% 4% 4%;
  transform-origin: 100% 50%;
  transform: translatez(-64px) scalex(-1) translatex(100%);
  background: #f5f5f5;
}

.left-side:nth-child(64) {
  transform: translatez(64px) scalex(-1) translatex(100%) rotatey(180deg);
}

.page:nth-child(65) {
  padding: 5% 4% 4% 5%;
  transform-origin: 0% 50%;
  transform: translatez(-65px);
  background: #f5f5f5;
}

.left-side:nth-child(65) {
  transform: translatez(65px) rotatey(-180deg);
}

.page:nth-child(66) {
  padding: 5% 5% 4% 4%;
  transform-origin: 100% 50%;
  transform: translatez(-66px) scalex(-1) translatex(100%);
  background: #f5f5f5;
}

.left-side:nth-child(66) {
  transform: translatez(66px) scalex(-1) translatex(100%) rotatey(180deg);
}

.page:nth-child(67) {
  padding: 5% 4% 4% 5%;
  transform-origin: 0% 50%;
  transform: translatez(-67px);
  background: #f5f5f5;
}

.left-side:nth-child(67) {
  transform: translatez(67px) rotatey(-180deg);
}

.page:nth-child(68) {
  padding: 5% 5% 4% 4%;
  transform-origin: 100% 50%;
  transform: translatez(-68px) scalex(-1) translatex(100%);
  background: #f5f5f5;
}

.left-side:nth-child(68) {
  transform: translatez(68px) scalex(-1) translatex(100%) rotatey(180deg);
}

.page:nth-child(69) {
  padding: 5% 4% 4% 5%;
  transform-origin: 0% 50%;
  transform: translatez(-69px);
  background: #f5f5f5;
}

.left-side:nth-child(69) {
  transform: translatez(69px) rotatey(-180deg);
}

.page:nth-child(70) {
  padding: 5% 5% 4% 4%;
  transform-origin: 100% 50%;
  transform: translatez(-70px) scalex(-1) translatex(100%);
  background: #ccc;
}

.left-side:nth-child(70) {
  transform: translatez(70px) scalex(-1) translatex(100%) rotatey(180deg);
}

.page:nth-child(71) {
  padding: 5% 4% 4% 5%;
  transform-origin: 0% 50%;
  transform: translatez(-71px);
  background: #ccc;
}

.left-side:nth-child(71) {
  transform: translatez(71px) rotatey(-180deg);
}

.page:nth-child(72) {
  padding: 5% 5% 4% 4%;
  transform-origin: 100% 50%;
  transform: translatez(-72px) scalex(-1) translatex(100%);
  background: #ccc;
}

.left-side:nth-child(72) {
  transform: translatez(72px) scalex(-1) translatex(100%) rotatey(180deg);
}

.page:nth-child(73) {
  padding: 5% 4% 4% 5%;
  transform-origin: 0% 50%;
  transform: translatez(-73px);
  background: #ccc;
}

.left-side:nth-child(73) {
  transform: translatez(73px) rotatey(-180deg);
}

.page:nth-child(74) {
  padding: 5% 5% 4% 4%;
  transform-origin: 100% 50%;
  transform: translatez(-74px) scalex(-1) translatex(100%);
  background: #ccc;
}

.left-side:nth-child(74) {
  transform: translatez(74px) scalex(-1) translatex(100%) rotatey(180deg);
}

.page:nth-child(75) {
  padding: 5% 4% 4% 5%;
  transform-origin: 0% 50%;
  transform: translatez(-75px);
  background: #ccc;
}

.left-side:nth-child(75) {
  transform: translatez(75px) rotatey(-180deg);
}

.page:nth-child(76) {
  padding: 5% 5% 4% 4%;
  transform-origin: 100% 50%;
  transform: translatez(-76px) scalex(-1) translatex(100%);
  background: #ccc;
}

.left-side:nth-child(76) {
  transform: translatez(76px) scalex(-1) translatex(100%) rotatey(180deg);
}

.page:nth-child(77) {
  padding: 5% 4% 4% 5%;
  transform-origin: 0% 50%;
  transform: translatez(-77px);
  background: #ccc;
}

.left-side:nth-child(77) {
  transform: translatez(77px) rotatey(-180deg);
}

.page:nth-child(78) {
  padding: 5% 5% 4% 4%;
  transform-origin: 100% 50%;
  transform: translatez(-78px) scalex(-1) translatex(100%);
  background: #ccc;
}

.left-side:nth-child(78) {
  transform: translatez(78px) scalex(-1) translatex(100%) rotatey(180deg);
}

.page:nth-child(79) {
  padding: 5% 4% 4% 5%;
  transform-origin: 0% 50%;
  transform: translatez(-79px);
  background: #ccc;
}

.left-side:nth-child(79) {
  transform: translatez(79px) rotatey(-180deg);
}

.page:nth-child(80) {
  padding: 5% 5% 4% 4%;
  transform-origin: 100% 50%;
  transform: translatez(-80px) scalex(-1) translatex(100%);
  background: #f5f5f5;
}

.left-side:nth-child(80) {
  transform: translatez(80px) scalex(-1) translatex(100%) rotatey(180deg);
}

.page:nth-child(81) {
  padding: 5% 4% 4% 5%;
  transform-origin: 0% 50%;
  transform: translatez(-81px);
  background: #f5f5f5;
}

.left-side:nth-child(81) {
  transform: translatez(81px) rotatey(-180deg);
}

.page:nth-child(82) {
  padding: 5% 5% 4% 4%;
  transform-origin: 100% 50%;
  transform: translatez(-82px) scalex(-1) translatex(100%);
  background: #f5f5f5;
}

.left-side:nth-child(82) {
  transform: translatez(82px) scalex(-1) translatex(100%) rotatey(180deg);
}

.page:nth-child(83) {
  padding: 5% 4% 4% 5%;
  transform-origin: 0% 50%;
  transform: translatez(-83px);
  background: #f5f5f5;
}

.left-side:nth-child(83) {
  transform: translatez(83px) rotatey(-180deg);
}

.page:nth-child(84) {
  padding: 5% 5% 4% 4%;
  transform-origin: 100% 50%;
  transform: translatez(-84px) scalex(-1) translatex(100%);
  background: #f5f5f5;
}

.left-side:nth-child(84) {
  transform: translatez(84px) scalex(-1) translatex(100%) rotatey(180deg);
}

.page:nth-child(85) {
  padding: 5% 4% 4% 5%;
  transform-origin: 0% 50%;
  transform: translatez(-85px);
  background: #f5f5f5;
}

.left-side:nth-child(85) {
  transform: translatez(85px) rotatey(-180deg);
}

.page:nth-child(86) {
  padding: 5% 5% 4% 4%;
  transform-origin: 100% 50%;
  transform: translatez(-86px) scalex(-1) translatex(100%);
  background: #f5f5f5;
}

.left-side:nth-child(86) {
  transform: translatez(86px) scalex(-1) translatex(100%) rotatey(180deg);
}

.page:nth-child(87) {
  padding: 5% 4% 4% 5%;
  transform-origin: 0% 50%;
  transform: translatez(-87px);
  background: #f5f5f5;
}

.left-side:nth-child(87) {
  transform: translatez(87px) rotatey(-180deg);
}

.page:nth-child(88) {
  padding: 5% 5% 4% 4%;
  transform-origin: 100% 50%;
  transform: translatez(-88px) scalex(-1) translatex(100%);
  background: #f5f5f5;
}

.left-side:nth-child(88) {
  transform: translatez(88px) scalex(-1) translatex(100%) rotatey(180deg);
}

.page:nth-child(89) {
  padding: 5% 4% 4% 5%;
  transform-origin: 0% 50%;
  transform: translatez(-89px);
  background: #f5f5f5;
}

.left-side:nth-child(89) {
  transform: translatez(89px) rotatey(-180deg);
}

.page:nth-child(90) {
  padding: 5% 5% 4% 4%;
  transform-origin: 100% 50%;
  transform: translatez(-90px) scalex(-1) translatex(100%);
  background: #ccc;
}

.left-side:nth-child(90) {
  transform: translatez(90px) scalex(-1) translatex(100%) rotatey(180deg);
}

.page:nth-child(91) {
  padding: 5% 4% 4% 5%;
  transform-origin: 0% 50%;
  transform: translatez(-91px);
  background: #ccc;
}

.left-side:nth-child(91) {
  transform: translatez(91px) rotatey(-180deg);
}

.page:nth-child(92) {
  padding: 5% 5% 4% 4%;
  transform-origin: 100% 50%;
  transform: translatez(-92px) scalex(-1) translatex(100%);
  background: #ccc;
}

.left-side:nth-child(92) {
  transform: translatez(92px) scalex(-1) translatex(100%) rotatey(180deg);
}

.page:nth-child(93) {
  padding: 5% 4% 4% 5%;
  transform-origin: 0% 50%;
  transform: translatez(-93px);
  background: #ccc;
}

.left-side:nth-child(93) {
  transform: translatez(93px) rotatey(-180deg);
}

.page:nth-child(94) {
  padding: 5% 5% 4% 4%;
  transform-origin: 100% 50%;
  transform: translatez(-94px) scalex(-1) translatex(100%);
  background: #ccc;
}

.left-side:nth-child(94) {
  transform: translatez(94px) scalex(-1) translatex(100%) rotatey(180deg);
}

.page:nth-child(95) {
  padding: 5% 4% 4% 5%;
  transform-origin: 0% 50%;
  transform: translatez(-95px);
  background: #ccc;
}

.left-side:nth-child(95) {
  transform: translatez(95px) rotatey(-180deg);
}

.page:nth-child(96) {
  padding: 5% 5% 4% 4%;
  transform-origin: 100% 50%;
  transform: translatez(-96px) scalex(-1) translatex(100%);
  background: #ccc;
}

.left-side:nth-child(96) {
  transform: translatez(96px) scalex(-1) translatex(100%) rotatey(180deg);
}

.page:nth-child(97) {
  padding: 5% 4% 4% 5%;
  transform-origin: 0% 50%;
  transform: translatez(-97px);
  background: #ccc;
}

.left-side:nth-child(97) {
  transform: translatez(97px) rotatey(-180deg);
}

.page:nth-child(98) {
  padding: 5% 5% 4% 4%;
  transform-origin: 100% 50%;
  transform: translatez(-98px) scalex(-1) translatex(100%);
  background: #ccc;
}

.left-side:nth-child(98) {
  transform: translatez(98px) scalex(-1) translatex(100%) rotatey(180deg);
}

.page:nth-child(99) {
  padding: 5% 4% 4% 5%;
  transform-origin: 0% 50%;
  transform: translatez(-99px);
  background: #ccc;
}

.left-side:nth-child(99) {
  transform: translatez(99px) rotatey(-180deg);
}

.page:nth-child(100) {
  padding: 5% 5% 4% 4%;
  transform-origin: 100% 50%;
  transform: translatez(-100px) scalex(-1) translatex(100%);
  background: #f5f5f5;
}

.left-side:nth-child(100) {
  transform: translatez(100px) scalex(-1) translatex(100%) rotatey(180deg);
}

.cover-front:nth-child(1) {
  text-align: center;
  background: linear-gradient(#124f62, #1d5d70) 50% 50%/80% 86% no-repeat,
    linear-gradient(#9dff00, #ddff00) 50% 50%/90% 93% no-repeat,
    linear-gradient(#1f1e37, #4d4d66) no-repeat;
}
.cover-front:nth-child(1) h1 {
  font-family: "Lora", serif;
  font-size: 45px;
  color: #c9d300;
  margin-top: 30px;
  text-transform: uppercase;
}
.cover-front:nth-child(1) h2 {
  font-family: "EB Garamond", serif;
  font-size: 24px;
  color: #ffee00;
  position: relative;
  top: 0%;
}
.cover-front:nth-child(1) .hat {
  font-size: 100px;
  color: #134a78;
  position: relative;
  top: 3%;
}

p {
  margin-bottom: 4%;
  font-family: "EB Garamond", serif;
  font-size: 16px;
}

.page:nth-child(3) p:first-of-type:first-letter {
  font-size: 32px;
}

.instruction {
  left: calc(50% - 150px);
  font-size: 26px;
  font-family: "EB Garamond", serif;
  color: #0009;
  box-sizing: border-box;
  border-radius: 2px solid red;
  padding: 10px 15px;
  margin-top: 10%;
}

    </style>
  </head>
  <body>
    <div class="motive">
      <h2>
        I write this Beautiful Book for You . <br />
        You Help me In Every Situation without judging me.
        <br />
        <span> Thank you For Everything💖.</span>
      </h2>
    </div>
    <div class="instruction" style="color: rgba(128, 108, 108, 0.61);"><b></b></div>
    <div class="book">
      <div class="page cover-front" onclick="movePage(this, 1)">
        <h1>Happy</h1>
        <h1>Rakhhiiee dii</h1>
        <h1>💖</h1>
        <img src="https://res.cloudinary.com/dnmzvkfkn/image/upload/v1754725218/IMG_20241107_184110_njamw6.jpg" alt="" style="width: 270px; aspect-ratio: auto 320 / 240; height: 260px; border-radius: 30px; border-color: rgb(163, 152, 137);">
        <div class="hat"><i class="fab fa-pied-piper-hat"></i></div>
        <h2> from Ritesh💖</h2>
      </div>
      <div class="page cover-front" onclick="movePage(this, 2)"></div>
      <div class="page text-page" onclick="movePage(this, 3)">
        <p>
          hey didi, i am Ritesh 🤞💖.
        </p>
        <p>
          Having a sister like you is a blessing beyond words. You’ve been my protector, confidant, and best friend. On this Raksha Bandhan, I wish you all the happiness, love, and success that you so richly deserve. 
          <b>Happy Raksha Bandhan!</b>
        </p>
<video src="https://res.cloudinary.com/dnmzvkfkn/video/upload/v1754733187/WhatsApp_Video_2025-08-09_at_13.30.30_d4c372c7_ni6nsq.mp4" width="320" height="240"autoplay controls loop></video>
        <br /><br />
        <p>Note: Play the video before reading further.</p>

        <br /><br /><br />
        <p>Please turn the page...</p>
      </div>
      <div class="page text-page" onclick="movePage(this, 4)">
        <p>
          Sisters are like angels who lift us to our feet when our wings forget how to fly. 
          On this Raksha Bandhan, I want to tell you that I’m always here for you, just like 
          you’ve always been for me. <b>Happy Rakhi, sis!🤞💖</b>
        </p>
        <p>
          Even though we may not be together today, the bond we share grows stronger with every passing day.
          Sending you lots of love and good wishes this Raksha Bandhan. Miss you, sister!
          To the most amazing sister in the world, thank you for all the love, care, and protection you've given me. 
          On this Rakhi, I wish you all the happiness and success in the world. 
          <b>Happy Raksha Bandhan!</b>
        </p>
        <p>
          Though we may not always be together, the love and connection we have remain strong, no matter the distance. 
          Your presence in my life has been a source of strength, 
          joy, and comfort. I cherish every moment we’ve spent together 
          and look forward to creating many more memories in the future.🏵🏵🏵
        </p>
        <p>
          On this Raksha Bandhan, I wish you all the happiness, success, 
          and love in the world. May our bond continue to grow stronger with each passing day. 
          Thank you for being not just a sister, but also a friend, a confidant, 
          and a guiding light in my life. Happy Raksha Bandhan!
        </p>
      </div>
      <div class="page text-page" onclick="movePage(this, 5)">
        <img src="data:image/jpeg;base64,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" alt="" width="320" height="240">
        <p>
          Your unwavering belief in me has pushed me to achieve things I never thought possible, and I want you to know how much that means to me.
        </p>
        <p>
          As we celebrate this Raksha Bandhan, I wish you nothing but happiness, success, and fulfillment in everything you do. 
          May you continue to shine brightly, and may our bond grow stronger with each passing day. 
          Thank you for being the incredible sister you are, and for filling my life with so much love and joy. Happy Raksha Bandhan, dear sister!🌸🌸🌸
        </p>  
      </div>
      <div class="page text-page" onclick="movePage(this, 6)">
        <p>
          Raksha Bandhan fills my heart with warmth and nostalgia. I find myself reminiscing about the countless moments we've shared, each one contributing to the unbreakable bond we have today. From our childhood antics to the deep friendship we've built over the years, every memory with you is a treasure I hold dear. 
          You’ve always been there, not just as a sister, but as someone who understands me in ways no one else can.
        </p>
        <p>
          On this Raksha Bandhan, I am reminded of the countless times you've stood up for me and protected me. You've always had my back, no matter the situation, and that sense of security you provide is something I cherish deeply.
          It's comforting to know that no matter what challenges life throws our way, we’ll face them together, just as we always have.
        </p>
      </div>
      <div class="page text-page">
        <p>
          On this Raksha Bandhan, I want to express just how much you mean to me. You are more than just a sister; you are my best friend, my advisor, and my biggest supporter. I couldn’t imagine my life without you in it. As we tie the rakhi this year,
          I pray that our bond continues to grow stronger and that you are blessed with all the happiness in the world. Happy Raksha Bandhan!
        </p>
        
        <p>You are My Everything, Didi 💖.</p>

        <h2>Happiie Rakhii 🏵</h2>
        <br />
        <img src="data:image/jpeg;base64,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" alt="" width="320" height="240">
        <button id="botao1">YES Sure!</button>
      </div>
      <div class="page"></div>
      <div class="page"></div>
      <div class="page"></div>
      <div class="page"></div>
      <div class="page"></div>
      <div class="page"></div>
      <div class="page"></div>
      <div class="page"></div>
      <div class="page"></div>
      <div class="page"></div>
      <div class="page"></div>
      <div class="page"></div>
      <div class="page"></div>
      <div class="page"></div>
      <div class="page"></div>
      <div class="page"></div>
      <div class="page"></div>
      <div class="page"></div>
      <div class="page"></div>
      <div class="page"></div>
      <div class="page"></div>
      <div class="page"></div>
      <div class="page"></div>
      <div class="page"></div>
      <div class="page"></div>
      <div class="page"></div>
      <div class="page"></div>
      <div class="page"></div>
      <div class="page"></div>
      <div class="page"></div>
      <div class="page"></div>
      <div class="page"></div>
      <div class="page"></div>
      <div class="page"></div>
      <div class="page"></div>
      <div class="page"></div>
      <div class="page"></div>
      <div class="page"></div>
      <div class="page"></div>
      <div class="page"></div>
    </div>
    

    <script>
      document.getElementById("botao1").addEventListener("click", function () {
        alert("YAYY THANK U 😍❤ , Drop a Message when you are Free ..");
      });
    </script>
    <script>
        let currentPage = 1;

function toggleClass(e, toggleClassName) {
  if (e.className.includes(toggleClassName)) {
    e.className = e.className.replace(" " + toggleClassName, "");
  } else {
    e.className += " " + toggleClassName;
  }
}

function movePage(e, page) {
  if (page == currentPage) {
    currentPage += 2;
    toggleClass(e, "left-side");
    toggleClass(e.nextElementSibling, "left-side");
  } else if ((page = currentPage - 1)) {
    currentPage -= 2;
    toggleClass(e, "left-side");
    toggleClass(e.previousElementSibling, "left-side");
  }
}

    </script>
  </body>
</html>
