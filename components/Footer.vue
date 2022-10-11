<template>
  <div class="footer">
    <div class="footer__header">
      <h1 class="u-font-h1">
        We are for founders and designers. We are them and we believe in them.
      </h1>
      <button class="c-button c-button--secondary">
        Connect with a SENIOR designer
      </button>
    </div>
    <div class="footer__bottom">
      <div class="footer__bottom__socials">
        <p><a href="">Twitter</a></p>
        <p><a href="">Instagram</a></p>
        <p><a href="">team</a></p>
      </div>
      <div class="footer__bottom__copy">
        <p>© Design Capital</p>
        <p>
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
        </p>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.footer {
  &__header {
    background-color: $color-purple;
    border-radius: 8rem;
    margin-bottom: 10.2rem;
    padding: 6rem 6rem 22.4rem;
    position: relative;
    width: 100vw;
    left: calc(-50vw + 50%);

    h1 {
      color: white;
      line-height: 11.52rem;
      margin-bottom: 8rem;
    }
  }
  &__bottom {
    display: flex;
    justify-content: space-between;
    text-transform: uppercase;

    &__socials {
      display: flex;
      flex: 1;
      align-content: center;
      justify-content: space-between;
      max-width: 38rem;

      p {
        font-weight: 500;
        line-height: 2.64rem;
        font-size: 2.4rem;

        a {
          color: black;
          text-decoration: none;
        }
      }
    }
    &__copy {
      display: flex;
      width: 33rem;
      align-content: center;
      justify-content: space-between;

      p {
        font-weight: 500;
        line-height: 2.64rem;
        font-size: 2.4rem;
        color: #828282;
      }
    }
  }
}
</style>
