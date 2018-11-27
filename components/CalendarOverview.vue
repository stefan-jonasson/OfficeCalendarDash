<template>
  <div class="CalendarOverview">
    <div class="Header Day1">M</div>
    <div class="Header Day2">T</div>
    <div class="Header Day3">O</div>
    <div class="Header Day4">T</div>
    <div class="Header Day5">F</div>
    <div class="AllDay Day1">
      <ul><li class="User1">Växjö</li></ul>
      <ul><li class="User2">Konferens</li></ul>
    </div>
    <div class="AllDay Day2"/>
    <div class="AllDay Day3">
      <ul><li class="User3">BRSE Konf...</li></ul>
      <ul><li class="User2">BRSE Konf...</li></ul>
    </div>
    <div class="AllDay Day4"><ul><li class="User1">Växjö</li></ul></div>
    <div class="AllDay Day5"><ul><li class="User1">Föräldrarledig</li></ul></div>
  </div>
</template>

<style>
.CalendarOverview {
  display: grid;
  grid-column-gap: 1rem;
}

.CalendarOverview .Header {
  @apply text-center p-6 text-2xl;
}

.CalendarOverview li {
  @apply text-left;
}

.CalendarOverview > .Day1 {
  grid-column: 1;
}
.CalendarOverview > .Day2 {
  grid-column: 2;
}
.CalendarOverview > .Day3 {
  grid-column: 3;
}
.CalendarOverview > .Day4 {
  grid-column: 4;
}
.CalendarOverview > .Day5 {
  grid-column: 5;
}
</style>
