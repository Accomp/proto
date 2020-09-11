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
              <div>header</div>
            </vs-col>
          </vs-row>
          <vs-row>
            <vs-col w="12" class="character-pane_title">
              <div>image</div>
            </vs-col>
          </vs-row>
          <vs-row>
            <vs-col w="6" class="character-pane_preview">
              <div>weap 1</div>
            </vs-col>
            <vs-col w="6" class="character-pane_weapons">
              <div>weap 2</div>
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
  background: rgb(223, 11, 212);
  border: 2px solid #000;
  margin-bottom: 10px;
  padding-top: 100%;

  &:last-child {
    margin-bottom: 0;
  }
}
.character-pane_title {
  background: rgb(223, 11, 212);
  border: 2px solid #000;
}
.character-pane_preview {
  background: rgb(223, 11, 212);
  border: 2px solid #000;
}
.character-pane_weapons {
  background: rgb(223, 11, 212);
  border: 2px solid #000;
}
</style>
