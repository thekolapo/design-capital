<template>
  <footer class="footer">
    <div class="footer__header">
      <h1 class="u-font-h1">
        We are for founders and designers. We are them and we believe in them.
      </h1>
      <a
        href="https://app.getdesign.capital/get-started"
        target="_blank"
        class="c-button c-button--secondary"
      >
        Connect with a SENIOR designer
      </a>
    </div>
    <div class="footer__bottom">
      <div class="footer__links">
        <a class="c-link" href="" target="_blank">Twitter</a>
        <a class="c-link" href="" target="_blank">Instagram</a>
        <nuxt-link class="c-link" to="/team">Team</nuxt-link>
      </div>
      <div class="footer__copyright">
        <span>© Design Capital</span>
        <svg
          width="50"
          height="25"
          viewBox="0 0 50 25"
          fill="none"
          xmlns="http://www.w3.org/2000/svg"
        >
          <path
            d="M0 0H12.5C19.4036 0 25 5.59644 25 12.5C25 19.4036 19.4036 25 12.5 25H0V0Z"
            fill="#9D00FF"
          />
          <path
            d="M39.6074 24.5573C32.1778 24.5573 28 19.7867 28 12.4456V12.179C28 5.03999 32.6435 0 39.1751 0C42.4911 0 44.8784 1.16739 45.9716 3.23839V0.367618H49.5219V8.34292H45.5756C44.778 5.03999 42.7867 3.53866 39.5739 3.53866C35.3906 3.53866 32.6435 6.77424 32.6435 12.2127V12.412C32.6435 17.7859 35.1954 20.9878 39.5739 20.9878C42.8899 20.9878 45.1768 19.2872 45.6732 15.8833H49.9514C49.243 21.6501 45.2437 24.5573 39.6074 24.5573Z"
            fill="black"
          />
        </svg>
      </div>
    </div>
  </footer>
</template>

<style lang="scss" scoped>
.footer {
  &__header {
    position: relative;
    width: 100vw;
    left: calc(-50vw + 50%);
    background-color: $color-purple;
    border-radius: 8rem;
    margin-bottom: 10.2rem;
    padding: 6rem var(--layout-horizontal-padding) 22.4rem;

    @include screen('small') {
      padding-top: 4rem;
      padding-bottom: 8rem;
      border-radius: 4rem;
      margin-bottom: 4rem;
    }

    h1 {
      color: white;
      margin-bottom: 8rem;

      @include screen('small') {
        margin-bottom: 4.4rem;
      }
    }
  }
  &__bottom {
    display: flex;
    justify-content: space-between;

    @include screen('med-small') {
      flex-wrap: wrap;
    }

    @include screen('small') {
      font-size: 1.7rem;
    }
  }

  &__links {
    display: flex;
    flex: 1;
    align-content: center;
    text-transform: uppercase;

    @include screen('med') {
      width: 100%;
    }

    @include screen('med-small') {
      margin-bottom: 2.6rem;
    }

    a:not(:last-child) {
      margin-right: 2.4rem;
    }
  }

  &__copyright {
    display: flex;
    align-items: center;
    justify-content: space-between;

    @include screen('med-small') {
      width: 100%;

      svg {
        transform: scale(0.7);
      }
    }

    span {
      font-weight: 500;
      color: #828282;
      margin-right: 5.2rem;

      @include screen('med') {
        margin-right: 3rem;
      }
    }
  }
}
</style>
