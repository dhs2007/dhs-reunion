<template lang="jade">
.container
  .center
    h2.inline Discounted Hotel Rooms
    h4 ( available for June 16 & 17)
    <iframe src="https://www.google.com/maps/d/embed?mid=1jgKk4yWKPd1LfTq3sAmlRbhkFNg" width="640" height="400"></iframe>
  .cards
    .card
      div
        h5 Courtyard Marriott
        div 3 Eagle Rd, 06810
        div (203) 730-2228
        div Call-in only for discount
        div Discount ends May 16
    .card
      div
        h5 Crowne Plaza Danbury
        div 18 Old Ridgebury Rd, 06810
        div (203) 794-0600
        div Discount Group Code: <b>DHS</b>
        div Discount ends April 17
        div
          a(href="https://www.crowneplaza.com/redirect?path=hd&brandCode=cp&localeCode=en&regionCode=1&hotelCode=dxrcp&_PMID=99801505&GPC=DHS&viewfullsite=true")
            | Book Online
    .card
      div
        h5 Ethan Allen Hotel
        div 21 Lake Ave Ext, 06811
        div (203) 744-1776
        div Call-in only for discount
        div Discount ends May 19
    .card
      div
        h5 Hampton Inn
        div 81 Newtown Rd, 06810
        div (203) 748-6677
        div Discount Group Code: <b>DHS</b>
        div Discount ends May 16
        div
          a(href="http://hamptoninn3.hilton.com/en/hotels/connecticut/hampton-inn-danbury-DXRCTHX/index.html")
            | Book Online
</template>

<style lang="scss" scoped>
  h2.inline {
    margin-bottom: 0;
  }
  .cards .column {
    margin-top: 20px;
  }
  // .card {
  //   width: 320px;
  //   margin-left: auto;
  //   margin-right: auto;
  // }
  .center {
    text-align: center;
  }
  h5 {
    margin-bottom: 0;
  }
  @media screen and (min-width: 40em) {
    .cards {
      display: flex;
      justify-content: space-between;
      flex-wrap: wrap;
    }

    .card {
      margin-bottom: 1em;
      display: flex;
      width: 290px;
      /* width: calc(50% - 1em); */
    }
  } /* mq 40em*/

  @media screen and (min-width: 60em) {
    .cards {
      margin-top: inherit;
    }

    .card {
      margin-bottom: 2em;
      display: flex;
      width: 290px;
      /* width: calc(33% - 1em); */
    }
  } /* mq 60em*/
</style>
