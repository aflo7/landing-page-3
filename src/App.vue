<script setup>
import Nav from './components/Nav.vue';
</script>

<template>
    <div
      style="
        display: flex;
        justify-content: center;
        background-color: rgb(24, 24, 24);
      "
    >
      <Nav />
    </div>
    <div class="germantown" style="height: 400px;"></div>

    <div
      style="
        display: flex;
        justify-content: center;
        background-color: rgb(24, 24, 24);
        color: white;
        padding: 40px;
      "
    >
      <div style="width: 1100px; display: flex; gap: 50px">
        <p style="font-size: 3rem; width: 1600px">
          Love where you live, and feel like you belong.
        </p>
        <div>
          <p style="font-size: 2rem">Made By Andres Flores</p>
          <p style="font-size: 1.2rem">
            For us, from day one, it's always been about building connections.
            We're not just building apartments, restaurants, pools and gyms;
            we're building places for people to engage, to connect, to be
            themselves. We're building places to call home.
          </p>
        </div>
      </div>
    </div>

    <div style="display: flex; justify-content: center">
      <div class="grid-container">
        <div>Andres Flores</div>
        <div>Andres Flores</div>
        <div>Andres Flores</div>
        <div>Andres Flores</div>
        <div>Andres Flores</div>
        <div>Andres Flores</div>
      </div>
    </div>

    <div
      style="
        display: flex;
        justify-content: center;
        color: white;
        background-color: rgb(26, 26, 26);
        padding: 40px;
      "
    >
      <div
        style="width: 1100px; display: flex; flex-direction: column; gap: 40px"
      >
        <div style="display: flex; gap: 100px">
          <div class="left-footer">
            <div>Locations</div>
            <div>FAQ</div>
            <div>The Goat</div>
            <div>Collective House Realty</div>
            <div>Code</div>
          </div>
          <div class="left-footer">
            <div>Contact</div>
            <div>Terms + Conditions</div>
            <div>Privacy</div>
            <div>Made By Andres Flores</div>
          </div>
        </div>
        <div style="display: flex; gap: 40px; align-items: center">
          <div>Sign up for updates, news, and more.</div>
          <div style="display: flex; gap: 10px">
            <input
              type="text"
              placeholder="email address"
              style="padding: 10px; border: none"
            />
            <button type="submit" style="padding: 10px" id="submitBtn">
              Submit
            </button>
          </div>
        </div>
      </div>
    </div>
</template>

<style scoped></style>
