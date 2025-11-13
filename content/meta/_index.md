+++
title = "Meta: System of Interest"
template = "meta.html"
+++

<div class="system-of-interest">
  <svg class="connections" viewBox="0 0 1000 700" preserveAspectRatio="xMidYMid meet">
    <path d="M 500 150 L 500 300" stroke="#000" stroke-width="2" fill="none"/>
    <path d="M 500 150 L 500 120 Q 500 100 480 100 L 170 100 Q 150 100 150 120 L 150 300" stroke="#000" stroke-width="2" fill="none"/>
    <path d="M 500 150 L 500 120 Q 500 100 520 100 L 830 100 Q 850 100 850 120 L 850 300" stroke="#000" stroke-width="2" fill="none"/>
    <path d="M 240 365 L 360 365" stroke="#000" stroke-width="2" fill="none"/>
    <path d="M 640 365 L 760 365" stroke="#000" stroke-width="2" fill="none"/>
    <path d="M 150 400 L 150 610 Q 150 630 170 630 L 420 630" stroke="#000" stroke-width="2" fill="none"/>
    <path d="M 500 400 L 500 630" stroke="#000" stroke-width="2" fill="none"/>
    <path d="M 850 400 L 850 610 Q 850 630 830 630 L 580 630" stroke="#000" stroke-width="2" fill="none"/>
  </svg>
  <div class="pillar-container">
    <div class="row row-top">
      <a href="#eight-cosmoses" class="pillar-box cosmoses">
        <h2>THE EIGHT<br>RECIPROCAL<br>COSMOSES</h2>
      </a>
    </div>
    <div class="row row-middle">
      <a href="#spiritual-disjunction" class="pillar-box disjunction">
        <h2>THE SPIRITUAL<br>DISJUNCTION</h2>
      </a>
      <a href="#five-tasks" class="pillar-box tasks">
        <h2>THE FIVE TASKS<br>OF STEWARDSHIP</h2>
      </a>
      <a href="#sevenfold-work" class="pillar-box sevenfold">
        <h2>THE SEVENFOLD<br>WORK</h2>
      </a>
    </div>
    <div class="row row-bottom">
      <a href="#biosphere-recursion" class="pillar-box biosphere">
        <h2>THE BIOSPHERE<br>RECURSION</h2>
      </a>
    </div>
  </div>
</div>

<style>
.system-of-interest {
  position: relative;
  width: 100%;
  max-width: 900px;
  margin: 0 auto;
  padding: 2rem 0;
}
.connections {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  pointer-events: none;
  z-index: 1;
}
.pillar-container {
  position: relative;
  z-index: 10;
  display: flex;
  flex-direction: column;
  gap: 3rem;
  align-items: center;
}
.row {
  display: flex;
  justify-content: center;
  gap: 2rem;
  width: 100%;
}
.row-top,
.row-bottom {
  justify-content: center;
}
.row-middle {
  justify-content: space-between;
  max-width: 800px;
}
.pillar-box {
  padding: 1.5rem 2rem;
  border-radius: 20px;
  border: 3px solid #000;
  text-align: center;
  box-shadow: 0 4px 6px rgba(0,0,0,0.1);
  min-width: 220px;
  text-decoration: none;
  display: block;
}
.pillar-box h2 {
  margin: 0;
  font-size: 1.1rem;
  font-weight: 700;
  line-height: 1.3;
  color: #000;
}
.cosmoses {
  background: #FFEB3B;
}
.disjunction {
  background: #FF8A65;
}
.tasks {
  background: #CE93D8;
}
.sevenfold {
  background: #64B5F6;
}
.biosphere {
  background: #81C784;
}
@media (max-width: 768px) {
  .system-of-interest {
    margin: 3rem auto;
    padding: 2rem;
  }
  .row-middle {
    flex-direction: column;
    align-items: center;
  }
  .pillar-box {
    min-width: 200px;
  }
  .connections {
    display: none;
  }
}
</style>
