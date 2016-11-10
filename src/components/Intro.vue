<template lang="jade">
  div
    h1 Danbury High School
    h2 Class of 2007 Reunion
    h3 The Details
    ul
      li Portugese Club
      li Saturday, June 17 2017
      li 5:00pm to 10:00pm
      li Open Bar & Buffett Style
</template>

<style lang="scss" scoped>
  h1 {
    font-size:9vw;
    text-align: center;
  }
  h2 {
    font-size:5vw;
    text-align: center;
  }
  h3 {
    font-weight: 200;
    text-decoration:underline;
    margin-top:120px;
    font-size: 3rem;
    text-align: center;
  }
  ul {
    width: 320px;
    margin-left:auto;
    margin-right:auto;
    li {
      font-size: 1.5rem;
    }
  }
  @media screen and (max-width: 420px) {
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
    }
    ul {
      width: 260px;
      li {
        font-size:1rem;
      }
    }
  }

</style>
