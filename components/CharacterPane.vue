<template>
  <section class="character-pane">
    <vs-row justify="space-between" align="stretch">
      <vs-col w="2" class="character-pane_left">
        <div class="gear-slot"></div>
        <div class="gear-slot"></div>
        <div class="gear-slot"></div>
        <div class="gear-slot"></div>
        <div class="gear-slot"></div>
        <div class="gear-slot"></div>
        <div class="gear-slot"></div>
        <div class="gear-slot"></div>
      </vs-col>
      <vs-col w="7">
        <div class="character-preview">
          <vs-row>
            <vs-col w="12" class="character-pane_title">
              <div class="title-slot">
                <div class="title-name">Accomp</div>
                <div class="title-class">Assassination Rogue</div>
                <div class="title-level">Level 120</div>
              </div>
            </vs-col>
          </vs-row>
          <vs-row>
            <vs-col w="12" class="character-pane_preview">
              <div class="preview-slot"></div>
            </vs-col>
          </vs-row>
          <vs-row>
            <vs-col w="6" class="character-pane_weapon">
              <div class="weapon-slot"></div>
            </vs-col>
            <vs-col w="6" class="character-pane_weapon">
              <vs-tooltip bottom>
                <div class="weapon-slot"></div>
                <template #tooltip> This is a WIP. </template>
              </vs-tooltip>
            </vs-col>
          </vs-row>
        </div>
      </vs-col>
      <vs-col w="2" class="character-pane_gear-right">
        <div class="gear-slot"></div>
        <div class="gear-slot"></div>
        <div class="gear-slot"></div>
        <div class="gear-slot"></div>
        <div class="gear-slot"></div>
        <div class="gear-slot"></div>
        <div class="gear-slot"></div>
        <div class="gear-slot"></div>
      </vs-col>
    </vs-row>
  </section>
</template>

<style lang="scss">
.character-pane {
  background: rgba(0, 0, 0, 0.7);
  border: 2px solid #000;
  padding: 20px;
  width: calc(100% - 20px);
}
.gear-slot {
  background: url('https://i.imgur.com/BxAxImN.png');
  background-size: cover;
  border: 2px solid #000;
  margin-bottom: 10px;
  padding-top: 100%;

  &:last-child {
    margin-bottom: 0;
  }
}
.character-pane_title {
  background: rgba(0, 0, 0, 0.8);
  border: 2px solid #000;
  color: #fff;
  margin-bottom: 10px;
}
.title-slot {
  text-align: center;
}
.character-pane_preview {
  background: url('https://i.imgur.com/qU1w585.jpg') center -550px;
  border: 2px solid #000;
  margin-bottom: 10px;
}
.preview-slot {
  padding-top: 150%;
}
.character-pane_weapon {
  padding-right: 5px;

  &:last-child {
    padding-left: 5px;
    padding-right: 0;
  }
}
.weapon-slot {
  background: rgb(223, 11, 212);
  border: 2px solid #000;
  padding-top: 50%;
}
</style>
