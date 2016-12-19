<template lang="jade">
  section
    h1 Danbury High School
    h2 Class of 2007 Reunion
    .container
      .row
        .columns.six.text-right
          img(src="../assets/dhs-mascot.png")
        .columns.six
          h3 The Details
          ul
            li Portugese Club
            li Saturday, June 17 2017
            li 5:00pm to 10:00pm
            li Open Bar & Buffet Style
</template>

<style lang="scss" scoped>
  h1 {
    font-size:9vw;
    text-align: center;
    color: #0D47A1;
    font-weight: 400;
  }
  h2 {
    font-size:5vw;
    text-align: center;
    color: #0D47A1;
  }
  h3 {
    font-weight: 800;
    margin-top:120px;
    font-size: 3rem;
    color: #0D47A1;
  }
  ul {
    width: 320px;
    li {
      font-size: 1.5rem;
      color: #2C3F77;
    }
  }
  .text-center {
    text-align: center;
  }
  .text-right {
    text-align: right;
  }
  img {
    padding-right: 20px;
    width: 200px;
  }
  @media screen and (max-width: 560px) {
    h1 {
      font-size:2rem;
      font-weight:500;
      margin-bottom:10px
    }
    h2 {
      font-size:1.8rem;
      font-weight:400;
    }
    h3{
      font-size:1.5rem;
      margin-top:60px;
      width: 260px;
      margin-right: auto;
      margin-left: auto;
    }
    ul {
      width: 260px;
      margin-right: auto;
      margin-left: auto;
      li {
        font-size:1rem;
      }
    }
    img {
      display: none;
    }
  }

</style>
