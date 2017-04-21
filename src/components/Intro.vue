<template lang="jade">
  section
    h1 Danbury High School
    h2 Class of 2007 Reunion
    .container
      .row
        .columns.six.text-right
          img.hidden-xs(src="../assets/dhs-mascot.png")
          .text-center.visible-xs
            img(src="../assets/dhs-hat.png")

        .columns.six
          h3 The Details
          ul
            li
              | Portuguese Club&nbsp;
              small
                a(href="https://goo.gl/maps/vShdyXC5KEp" target="_blank") (view map)
            li Saturday, June 17 2017
            li 7:00pm to Midnight
            li Open Bar & Buffet Style
            li Ticket Price: $50
            li.center
              a(href="https://www.eventbrite.com/e/danbury-high-school-2007-class-reunion-tickets-30853663137?ref=elink", class="button button-primary")
                | Purchase Tickets
</template>

<style lang="scss">
  li.helped {
    margin-bottom: 5px;
  }
  li.helper {
    list-style: none;
    text-align: center;
    font-size: 13px;
    font-weight: bold;
  }
  li.center {
    list-style: none;
    text-align: center;
  }
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
    margin-top:30px;
    font-size: 3rem;
    color: #0D47A1;
    margin-bottom: 5px;
  }
  h4 {
    font-size: 2rem;
  }
  .button.button-primary {
    background: #F5701C;
    border-color: #F5701C;
    &:hover {
      background: darken(#F5701C, 10%);
      border-color: #F5701C;
    }
  }
  ul {
    width: 320px;
    list-style-position: outside;
    list-style-type: none;
    li {
      font-size: 1.2rem;
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
  .visible-xs {
    display: none;
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
    h4 {
      font-size: 1rem;
    }
    ul {
      width: 260px;
      margin-right: auto;
      margin-left: auto;
      li {
        font-size:1rem;
      }
    }
    .hidden-xs {
      display: none;
    }
    .visible-xs {
      display: block;
    }
  }

</style>
