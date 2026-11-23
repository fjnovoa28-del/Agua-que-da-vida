
@import url('https://fonts.googleapis.com/css2?family=DM+Sans:wght@400;500;600;700&family=Manrope:wght@400;500;600;700;800&display=swap');

:root {
  --navy: #082f49;
  --blue: #087e9b;
  --cyan: #5dd5d0;
  --pale: #eaf7f5;
  --ink: #163447;
  --muted: #607783;
  --white: #fff;
}

* {
  box-sizing: border-box;
}

html {
  scroll-behavior: smooth;
}

body {
  margin: 0;
  font-family: 'DM Sans', sans-serif;
  color: var(--ink);
  background: white;
}

a {
  color: inherit;
  text-decoration: none;
}

.topbar {
  height: 76px;
  padding: 0 7%;
  display: flex;
  align-items: center;
  justify-content: space-between;
  background: white;
  position: sticky;
  top: 0;
  z-index: 10;
  box-shadow: 0 4px 22px #082f4910;
}

.brand {
  display: flex;
  align-items: center;
  gap: 10px;
  font: 800 15px Manrope, sans-serif;
  letter-spacing: 1px;
  color: var(--navy);
}

.brand-icon {
  font-size: 25px;
}

.brand-light {
  font-weight: 500;
  color: var(--blue);
}

nav {
  display: flex;
  gap: 34px;
  font-size: 13px;
  font-weight: 700;
  color: #47616e;
}

nav a:hover,
.text-link:hover {
  color: var(--blue);
}

.menu-toggle {
  display: none;
  border: 0;
  background: none;
  font-size: 25px;
}

.hero {
  min-height: 600px;
  background: linear-gradient(115deg,#07314b 0%,#075b72 58%,#078d9c 100%);
  color: white;
  padding: 95px 9% 35px;
  position: relative;
  overflow: hidden;
  display: flex;
  align-items: center;
}

.hero-content {
  position: relative;
  z-index: 2;
  max-width: 590px;
}

.eyebrow {
  font-size: 10px;
  font-weight: 800;
  letter-spacing: 2.2px;
  color: #38bdbb;
}

.hero h1,
.section h2,
.closing h2 {
  font: 800 clamp(38px,5.5vw,66px)/1.1 Manrope,sans-serif;
  letter-spacing: -2.5px;
  margin: 22px 0;
}

.hero h1 em,
.closing h2 em {
  font-style: normal;
  color: #73e2d5;
}

.hero p {
  font-size: 17px;
  line-height: 1.8;
  color: #d0e5e9;
  max-width: 500px;
}

.hero-actions {
  display: flex;
  align-items: center;
  gap: 24px;
  margin-top: 32px;
}

.btn {
  border: 0;
  border-radius: 30px;
  padding: 15px 23px;
  font-weight: 800;
  font-size: 13px;
  display: inline-flex;
  align-items: center;
  gap: 18px;
  cursor: pointer;
  transition: .2s;
}

.btn:hover {
  transform: translateY(-2px);
}

.btn-primary {
  background: #65ded1;
  color: #07394c;
}

.hero-note {
  font-size: 11px;
  color: #b5d6dc;
}

.hero-art {
  position: absolute;
  right: 4%;
  top: 8%;
  width: 47%;
  height: 85%;
  overflow: hidden;
  border-radius: 48% 52% 0 0;
  background: linear-gradient(#4fc4c7,#0a819b);
  opacity: .96;
}

.sun {
  position: absolute;
  width: 120px;
  height: 120px;
  background: #f8c77c;
  border-radius: 50%;
  right: 19%;
  top: 12%;
  box-shadow: 0 0 0 22px #f8c77c20;
}

.water-drop {
  position: absolute;
  z-index: 3;
  font-size: 150px;
  left: 39%;
  top: 23%;
  filter: drop-shadow(0 18px 18px #063b4c55);
}

.wave {
  position: absolute;
  width: 150%;
  height: 55%;
  left: -20%;
  border-radius: 48% 52% 0 0;
}

.wave-one {
  bottom: -18%;
  background: #073d59;
  transform: rotate(-8deg);
}

.wave-two {
  bottom: -28%;
  background: #0a7185;
  transform: rotate(7deg);
}

.leaf {
  position: absolute;
  color: #b5e7c7;
  font-size: 50px;
}

.leaf-one {
  left: 16%;
  top: 48%;
}

.leaf-two {
  right: 14%;
  top: 55%;
}

.hero-bottom {
  position: absolute;
  bottom: 25px;
  left: 9%;
  right: 9%;
  display: flex;
  justify-content: space-between;
  color: #9dc8d1;
  font-size: 9px;
  letter-spacing: 2px;
}

.section {
  padding: 100px 9%;
}

.section-heading h2,
.river-copy h2,
.quiz-intro h2,
.pledge h2 {
  font-size: clamp(32px,4vw,48px);
  letter-spacing: -1.8px;
  color: var(--navy);
}

.intro-grid {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 9%;
  margin: 30px 0 55px;
  line-height: 1.9;
  color: var(--muted);
  font-size: 15px;
}

.intro-grid .lead {
  font-size: 20px;
  line-height: 1.65;
  color: #24495a;
  font-weight: 600;
  margin: 0;
}

.fact-strip {
  display: grid;
  grid-template-columns: repeat(4,1fr);
  background: var(--pale);
  border-radius: 15px;
  padding: 25px 18px;
  gap: 10px;
}

.fact-strip div {
  display: flex;
  align-items: center;
  gap: 12px;
  justify-content: center;
  font-size: 12px;
  font-weight: 700;
}

.fact-strip strong {
  font-size: 24px;
}

.river-section {
  background: #f4f9f8;
  display: grid;
  grid-template-columns: 1.05fr .95fr;
  gap: 8%;
  align-items: center;
}

.river-image {
  height: 430px;
  border-radius: 7px;
  position: relative;
  overflow: hidden;
  background:
    linear-gradient(0deg,#063c54aa,transparent 60%),
    url('https://images.unsplash.com/photo-1437482078695-73f5ca6c96e2?auto=format&fit=crop&w=1200&q=85') center/cover;
}

.image-caption {
  position: absolute;
  bottom: 25px;
  left: 25px;
  color: white;
  font-size: 10px;
  letter-spacing: 2px;
  font-weight: 800;
}

.river-copy p {
  color: var(--muted);
  line-height: 1.85;
  font-size: 14px;
}

.text-link {
  display: inline-block;
  color: var(--blue);
  font-weight: 800;
  font-size: 13px;
  margin-top: 15px;
}

.centered {
  text-align: center;
  max-width: 650px;
  margin: 0 auto 45px;
}

.centered p {
  color: var(--muted);
  line-height: 1.7;
}

.action-grid {
  display: grid;
  grid-template-columns: repeat(4,1fr);
  gap: 16px;
}

.action-card {
  border: 1px solid #e2eeee;
  background: white;
  border-radius: 12px;
  padding: 25px 20px;
  text-align: left;
  display: flex;
  flex-direction: column;
  min-height: 210px;
  cursor: pointer;
  transition: .2s;
  color: var(--ink);
}

.action-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 12px 35px #0a536414;
  border-color: #9bdcd7;
}

.action-card span {
  font-size: 30px;
  margin-bottom: 18px;
}

.action-card b {
  font: 800 16px Manrope;
  color: var(--navy);
}

.action-card small {
  font-size: 12px;
  line-height: 1.6;
  color: var(--muted);
  margin-top: 8px;
}

.action-card i {
  font-size: 11px;
  font-style: normal;
  color: var(--blue);
  font-weight: 800;
  margin-top: auto;
  padding-top: 16px;
}

.tip-panel {
  margin-top: 18px;
  border-radius: 10px;
  background: #eaf7f5;
  padding: 16px 20px;
  display: flex;
  gap: 12px;
  align-items: center;
  color: #315765;
  font-size: 13px;
}

.tip-panel p {
  margin: 0;
}

.quiz-section {
  background: #082f49;
  color: white;
  display: grid;
  grid-template-columns: .8fr 1.2fr;
  gap: 8%;
  align-items: center;
}

.quiz-intro h2 {
  color: white;
}

.quiz-intro p {
  color: #c0d5dc;
  line-height: 1.8;
  font-size: 14px;
}

.quiz-stats {
  display: flex;
  gap: 12px;
  flex-wrap: wrap;
  margin-top: 25px;
}

.quiz-stats span {
  border: 1px solid #ffffff35;
  border-radius: 30px;
  padding: 9px 13px;
  font-size: 10px;
}

.quiz-card,
.result-card {
  background: white;
  color: var(--ink);
  border-radius: 16px;
  padding: 30px;
  box-shadow: 0 20px 60px #001e2d55;
}

.quiz-top {
  display: flex;
  justify-content: space-between;
  color: #66808c;
  font-size: 10px;
  font-weight: 800;
  letter-spacing: 1px;
}

.progress-track {
  height: 6px;
  background: #e6f0ef;
  border-radius: 10px;
  overflow: hidden;
  margin: 15px 0 25px;
}

.progress-track div {
  height: 100%;
  width: 0;
  background: #24b9ad;
  transition: .3s;
}

.quiz-card h3 {
  font: 800 21px/1.4 Manrope;
  color: var(--navy);
  margin: 25px 0;
}

.answers {
  display: grid;
  gap: 10px;
}

.answer {
  padding: 13px 15px;
  border: 1px solid #dce8e8;
  border-radius: 9px;
  background: white;
  text-align: left;
  font: 600 13px 'DM Sans';
  color: #355360;
  cursor: pointer;
}

.answer:hover:not(:disabled) {
  border-color: #28b6ac;
  background: #f1fbfa;
}

.answer.correct {
  background: #e3f8ee;
  border-color: #4ab981;
  color: #176b43;
}

.answer.wrong {
  background: #fff0ec;
  border-color: #e88c73;
  color: #9d3d2a;
}

.answer:disabled {
  cursor: default;
}

.feedback {
  min-height: 38px;
  font-size: 12px;
  line-height: 1.6;
  margin-top: 12px;
  color: #50707c;
}

.quiz-next {
  margin-top: 10px;
}

.quiz-next:disabled {
  opacity: .4;
  cursor: not-allowed;
  transform: none;
}

.result-card {
  text-align: center;
}

.result-card.hidden,
.hidden {
  display: none;
}

.result-icon {
  font-size: 50px;
}

.result-card h3 {
  font: 800 27px Manrope;
  color: var(--navy);
}

.result-score {
  font: 800 42px Manrope;
  color: #078d9c;
  margin: 18px;
}

.result-card p {
  color: var(--muted);
  line-height: 1.7;
}

.pledge {
  display: grid;
  grid-template-columns: .35fr 1fr;
  gap: 5%;
  align-items: start;
  background: #f3faf8;
}

.pledge-mark {
  font-size: 95px;
  text-align: center;
}

.pledge h2 {
  margin-top: 15px;
}

.pledge p {
  color: var(--muted);
  line-height: 1.7;
}

.pledge-list {
  display: grid;
  gap: 15px;
  margin: 25px 0;
}

.pledge-list label {
  display: flex;
  gap: 12px;
  align-items: center;
  font-size: 13px;
  font-weight: 600;
  color: #365766;
}

.pledge-list input {
  accent-color: #078d9c;
  width: 17px;
  height: 17px;
}

.pledge-progress {
  display: flex;
  align-items: center;
  gap: 15px;
}

.pledge-progress .progress-track {
  flex: 1;
  margin: 0;
}

.pledge-progress span {
  font-size: 11px;
  color: var(--muted);
  white-space: nowrap;
}

.pledge-message {
  font-weight: 700;
  color: #078d9c !important;
  font-size: 13px;
}

.closing {
  text-align: center;
  background: linear-gradient(120deg,#08718a,#06364f);
  color: white;
}

.closing h2 {
  font-size: clamp(35px,5vw,55px);
}

.closing p {
  color: #c6e1e4;
  margin: 25px 0;
}

.btn-light {
  background: white;
  color: var(--navy);
}

footer {
  background: #06283d;
  color: #a9c5cd;
  padding: 25px 9%;
  display: flex;
  justify-content: space-between;
  font-size: 9px;
  letter-spacing: 1px;
}

.modal {
  position: fixed;
  inset: 0;
  background: #001e2dcc;
  z-index: 30;
  display: grid;
  place-items: center;
  padding: 20px;
}

.modal-box {
  background: white;
  border-radius: 16px;
  padding: 35px;
  max-width: 440px;
  position: relative;
}

.modal-box > span {
  font-size: 10px;
  color: #078d9c;
  font-weight: 800;
  letter-spacing: 1px;
}

.modal-box h3 {
  font: 800 24px Manrope;
  color: var(--navy);
}

.modal-box p {
  color: var(--muted);
  line-height: 1.8;
}

.modal-box button {
  position: absolute;
  right: 18px;
  top: 12px;
  border: 0;
  background: none;
  font-size: 28px;
  cursor: pointer;
}

@media(max-width:850px) {
  .hero-art {
    right: -12%;
    width: 55%;
    opacity: .55;
  }

  .action-grid {
    grid-template-columns: repeat(2,1fr);
  }

  .quiz-section {
    grid-template-columns: 1fr;
    gap: 35px;
  }

  .river-section {
    gap: 5%;
  }

  .fact-strip {
    grid-template-columns: repeat(2,1fr);
    row-gap: 20px;
  }
}

@media(max-width:600px) {
  .topbar {
    height: 65px;
    padding: 0 6%;
  }

  .menu-toggle {
    display: block;
    color: var(--navy);
  }

  nav {
    display: none;
    position: absolute;
    top: 65px;
    left: 0;
    right: 0;
    background: white;
    padding: 20px 7%;
    flex-direction: column;
    gap: 18px;
    box-shadow: 0 12px 20px #001e2d15;
  }

  nav.open {
    display: flex;
  }

  .hero {
    min-height: 620px;
    padding: 80px 7% 60px;
    align-items: flex-start;
  }

  .hero-content {
    max-width: 100%;
  }

  .hero h1 {
    font-size: 43px;
  }

  .hero p {
    font-size: 15px;
  }

  .hero-art {
    width: 85%;
    height: 50%;
    top: 48%;
    right: -23%;
    opacity: .3;
  }

  .hero-bottom {
    left: 7%;
    right: 7%;
    font-size: 8px;
  }

  .section {
    padding: 72px 7%;
  }

  .section-heading h2,
  .river-copy h2,
  .quiz-intro h2,
  .pledge h2 {
    font-size: 34px;
  }

  .intro-grid {
    grid-template-columns: 1fr;
    gap: 15px;
  }

  .fact-strip {
    padding: 22px 10px;
  }

  .fact-strip div {
    justify-content: flex-start;
    font-size: 10px;
  }

  .river-section {
    grid-template-columns: 1fr;
  }

  .river-image {
    height: 280px;
  }

  .action-grid {
    gap: 10px;
  }

  .action-card {
    padding: 18px 14px;
    min-height: 205px;
  }

  .quiz-card,
  .result-card {
    padding: 22px 17px;
  }

  .quiz-card h3 {
    font-size: 18px;
  }

  .pledge {
    grid-template-columns: 1fr;
  }

  .pledge-mark {
    text-align: left;
    font-size: 65px;
  }

  .pledge-progress {
    align-items: flex-start;
    flex-direction: column;
  }

  .pledge-progress .progress-track {
    width: 100%;
    flex: auto;
  }

  .closing h2 {
    font-size: 37px;
  }

  footer {
    padding: 22px 7%;
    flex-direction: column;
    gap: 10px;
    line-height: 1.6;
  }
}
