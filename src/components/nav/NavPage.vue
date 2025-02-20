<template>
  <div class="nav">
    <div class="nav__wrapper">
      <img class="nav__img" :src="logo" alt="Logo" />
      <div class="nav__title">taski</div>
    </div>

    <ul class="nav__list">
      <li class="nav__list-item">
        <img :src="category" alt="category" />
        <p class="nav__list-title">Overview</p>
      </li>
      <li class="nav__list-item">
        <img :src="book" alt="book" />
        <p class="nav__list-title">Task</p>
      </li>
      <li class="nav__list-item">
        <img :src="mentor" alt="mentor" />
        <p class="nav__list-title">Mentors</p>
      </li>
      <li class="nav__list-item">
        <img :src="message" alt="mewssage" />
        <p class="nav__list-title">Message</p>
      </li>
      <li class="nav__list-item">
        <img :src="settings" alt="settings" />
        <p class="nav__list-title">Settings</p>
      </li>
    </ul>

    <div class="nav__help">
      <div class="nav__help-title">Help Center</div>

      <div class="nav__help-descr">
        Having Trouble in Learning. Please contact us for more questions.
      </div>

      <div class="nav__help-btn">Go To Help Center</div>
    </div>
  </div>
</template>

<script lang="ts">
import './navPage.scss'
import logo from '@/assets/logo.svg'
import category from '../icons/navIcons/category.svg'
import book from '../icons/navIcons/book.svg'
import mentor from '../icons/navIcons/octagon.svg'
import message from '../icons/navIcons/message.svg'
import settings from '../icons/navIcons/setting.svg'

export default {
  name: 'NavPage',
  data() {
    return {
      logo,
      category,
      book,
      mentor,
      settings,
      message,
    }
  },
}
</script>
