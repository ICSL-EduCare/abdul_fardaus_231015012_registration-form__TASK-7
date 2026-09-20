<template>
  <div class="page">
    <div class="left">
      <header class="header">
        <div class="logo">
          <img src="/icons/favicon-32x32.png" alt="Logo" />
        </div>

        <nav class="navigation">
          <q-btn flat label="SERVICES" no-caps />
          <q-btn flat label="OFFICES" no-caps class="active" />
          <q-btn flat label="TEAM" no-caps />
          <q-btn flat label="PHILOSOPHY" no-caps />
          <q-btn flat label="SPACES" no-caps />
        </nav>
      </header>

      <section class="team">
        <div class="team-info">
          <div class="team-label">OUR TEAM</div>

          <p>Lorraine Wolf</p>

          <h2>
            Technology<br />
            lawyer
          </h2>

          <a href="#" class="explore"> Explore </a>
        </div>

        <div class="person-area">
          <div class="circle"></div>

          <q-img
            src="/icons/girl.png"
            class="person"
            fit="contain"
            no-spinner
          />
        </div>
      </section>
    </div>

    <div class="right">
      <q-btn outline color="white" label="LOGIN" no-caps class="login-button" />

      <div class="content">
        <h1>
          Your legal advisers<br />
          for the problems<br />
          of this century
        </h1>

        <p>
          We offer solutions adapted to<br />
          today's needs
        </p>

        <q-btn
          color="white"
          text-color="negative"
          label="VIEW MORE"
          no-caps
          class="view-button"
        />
      </div>
    </div>
  </div>
</template>

<style lang="sass" scoped>

.page
  width: 1055px
  height: 653px
  margin: 0 auto
  display: flex
  overflow: hidden
  background: #ffffff

.left
  width: 64%
  height: 100%
  position: relative
  background: #ffffff

.header
  width: 100%
  height: 88px
  display: flex
  align-items: center
  padding: 0 42px
  box-sizing: border-box

.logo
  width: 38px
  height: 38px
  display: flex
  align-items: center
  justify-content: center
  flex-shrink: 0

  img
    width: 32px
    height: 32px
    object-fit: contain

.navigation
  display: flex
  align-items: center
  gap: 4px
  margin-left: 48px

  .q-btn
    min-height: 32px
    padding: 0 10px
    color: #222222
    font-family: Arial, sans-serif
    font-size: 9px
    font-weight: 500
    letter-spacing: 0.6px

  .active
    font-weight: 700

.team
  width: 100%
  height: calc(100% - 88px)
  display: flex
  position: relative
  overflow: hidden

.team-info
  width: 45%
  padding-left: 82px
  padding-top: 118px
  position: relative
  z-index: 5
  box-sizing: border-box

.team-label
  text-decoration: underline
  margin-bottom: 25px
  color: #777777
  font-family: Arial, sans-serif
  font-size: 19px
  font-weight: 600
  letter-spacing: 1.4px

.team-info p
  margin: 0 0 15px
  color: #333333
  font-family: Arial, sans-serif
  font-size: 19px

.team-info h2
  margin: 0
  color: #222222
  font-family: Georgia, "Times New Roman", serif
  font-size: 31px
  line-height: 1.05
  font-weight: 400

.explore
  display: inline-block
  margin-top: 36px
  color: #ff6468

  text-decoration: underline
  font-family: Arial, sans-serif
  font-size: 16px
  font-weight: 600

  &::after
    content: "→"
    margin-left: 9px
    font-size: 13px

.person-area
  width: 55%
  height: 100%
  position: relative
  display: flex
  align-items: center
  justify-content: center

.circle
  position: absolute
  width: 310px
  height: 310px
  top: 65px
  left: 20px
  z-index: 1
  border-radius: 50%
  background: #ff6468

.person
  position: absolute
  width: 310px
  height: 410px
  top: 25px
  left: 15px
  z-index: 2

.right
  width: 36%
  height: 100%
  position: relative
  overflow: hidden
  background: #ff6468
  color: #ffffff

.login-button
  position: absolute
  top: 35px
  right: 35px
  min-height: 30px
  padding: 0 20px
  border-color: rgba(255, 255, 255, 0.8)
  font-family: Arial, sans-serif
  font-size: 9px
  letter-spacing: 0.8px

.content
  position: absolute
  top: 185px
  left: 52px
  right: 30px

.content h1
  margin: 0
  color: #ffffff
  font-family: Georgia, "Times New Roman", serif
  font-size: 31px
  line-height: 1.08
  font-weight: 400

.content p
  margin: 25px 0 28px
  color: #ffffff
  font-family: Arial, sans-serif
  font-size: 11px
  line-height: 1.55

.view-button
  min-height: 35px
  padding: 0 22px
  font-family: Arial, sans-serif
  font-size: 9px
  font-weight: 600
  letter-spacing: 0.5px
</style>
