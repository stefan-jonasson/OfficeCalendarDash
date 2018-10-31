<template>
  <div class="DayQuote">
    <div class="Text Day">M 29</div>
    <div class="Text Month">okt</div>
    <div class="Text Quote">Build half a product,<br> not a half assed product
      <span>Jason Fried</span>
    </div>
  </div>
</template>

<style>
.DayQuote {
  @apply p-8;
}

.DayQuote > .Text {
  @apply font-hairline;
}

.DayQuote > .Text.Month {
  @apply text-3xl float-left pl-4 pt-2;
}

.DayQuote > .Text.Day {
  @apply text-big float-left;
}

.DayQuote > .Text.Quote {
  @apply text-2xl text-center absolute pin-r pin-b mb-16 mr-32 max-w-xs;
}

.DayQuote > .Text.Quote > span {
  @apply text-sm block  mt-3;
}

.DayQuote {
  background-image: url("data:image/svg+xml;utf8,<svg xmlns='http://www.w3.org/2000/svg' width='200' height='100'><polyline points='0,100 200,0 200,100' fill='rgb(38, 39, 41)'/></svg>");
  background-repeat: no-repeat;
  background-size: 100% 100%;
  height: 180px;
  position: absolute;
  left: 0;
  right: 0;
  text-align: left;
}
</style>
