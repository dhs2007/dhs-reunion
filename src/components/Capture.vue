<template lang="jade">
  .container
    form
      h3 Reserve Your Spot
      .row
        .eight.columns
          div
            label(for="FirstName") First Name
            input.u-full-width(type="text", placeholder="Brian")
          div
            label(for="LastName") Last Name
            input.u-full-width(type="text", placeholder="Peppers")
          div
            label(for="EmailAddress") Email Address
            input.u-full-width(type="email", placeholder="brianpeppers@aol.com")
          div
            label.vegan-selection
              input(type="checkbox")
              span.label-body I'd like a vegan meal
          input.button-primary(type="submit", value="Continue")
</template>

<style lang="scss" scoped>
  form {
    margin-top:100px;
    margin-left:auto;
    margin-right:auto;
    max-width:400px;
    padding:15px;
    border: 1px solid #cfcfcf;
    border-radius: 8px;
  }
</style>
