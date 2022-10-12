<template>
  <div class="home">
    <section class="home__hero">
      <h1 class="u-font-h1">Get backed by senior designers around the world</h1>
      <p class="home__hero-subtext">
        Connect with Senior designers and design experts who want to invest
        between $20k - $100k worth of design work in exceptional early-stage
        startups and pay in equity.
      </p>
      <button class="c-button">Connect with a SENIOR designer</button>
    </section>
    <section class="home__offers">
      <h1 class="u-font-h1">Why Design Capital?</h1>
      <div class="home__offers-list">
        <div class="home__offers-offer">
          <h3 class="u-font-h3">TAKE THE GUESSWORK OUT</h3>
          <p>
            We have a network of senior-level designers across brand, visual,
            product and web design, with years of experience working with some
            of the most successful startups across Africa and the emerging
            market at large.
          </p>
        </div>
        <div class="home__offers-offer">
          <h3 class="u-font-h3">MAKE THE SEARCH EASY</h3>
          <p>
            You get to choose from our pool of seasoned designers, and we also
            offer pairing recommendations between designers and startups. No
            more long months, asking for recommendations from friends, Twitter,
            and family.
          </p>
        </div>
        <div class="home__offers-offer">
          <h3 class="u-font-h3">SIMPLIFY THE ENGAGEMENT</h3>
          <p>
            Straightforward contracts and agreements that work for the startup
            and designer.
          </p>
        </div>
        <div class="home__offers-offer">
          <h3 class="u-font-h3">NOT MORE THAN __ EQUITY</h3>
          <p>
            Designers on Design Capital provide design services worth 20 000 USD
            to 100 000 USD, and never take more than ____ in equity.
          </p>
        </div>
      </div>
    </section>
    <section class="home__steps">
      <h1 class="u-font-h1">It's a 3 step process</h1>
      <div class="home__steps-list">
        <div class="home__steps-step">
          <!--prettier-ignore-->
          <svg width="97" height="88" viewBox="0 0 97 88" fill="none" xmlns="http://www.w3.org/2000/svg">
            <path d="M45.8101 86.8307L7.64441 46.7687C-3.10575 35.4846 -2.42879 16.9821 9.1142 6.59654C20.5657 -3.7067 37.9291 -1.70597 46.9785 10.9595L48.4999 13.0888L50.0214 10.9595C59.071 -1.70597 76.434 -3.7067 87.8858 6.59654C99.4288 16.9821 100.106 35.4846 89.3553 46.7687L51.1898 86.8307C49.7042 88.3898 47.2957 88.3898 45.8101 86.8307Z" fill="#9D00FF"/>
          </svg>
          <h3 class="u-font-h3">GETTING ON BOARD</h3>
          <p>
            We evaluate the startup and make sure they're a good fit. We welcome
            them on board if they are.
          </p>
        </div>
        <div class="home__steps-step">
          <!--prettier-ignore-->
          <svg width="218" height="99" viewBox="0 0 218 99" fill="none" xmlns="http://www.w3.org/2000/svg">
            <circle cx="49.5" cy="49.5" r="49" fill="white" stroke="black"/>
            <circle cx="168.5" cy="49.5" r="49.5" fill="#6AE692"/>
          </svg>
          <h3 class="u-font-h3">PAIRING</h3>
          <p>
            To facilitate the pairing stage we collect a deposit finders fee of
            $500, this will be completely refunded if the startup doesn't get
            engaged with a designer.
            <br />
            <br />
            We identify the start- up's needs and pair them with an interested
            designer(s) who fits. The startup chooses the designer to proceed
            with.
          </p>
        </div>
        <div class="home__steps-step">
          <!--prettier-ignore-->
          <svg width="139" height="108" viewBox="0 0 139 108" fill="none" xmlns="http://www.w3.org/2000/svg">
            <rect x="51.3773" y="64.6578" width="89.4103" height="32.4853" transform="rotate(-45 51.3773 64.6578)" fill="white" stroke="black"/>
            <rect x="23.6777" y="28.9013" width="77.3556" height="32.4853" transform="rotate(45 23.6777 28.9013)" fill="white" stroke="black"/>
          </svg>
          <h3 class="u-font-h3">ENGAGEMENT</h3>
          <p>
            Terms are documented and the agreement between designer and startup
            is settled.
          </p>
        </div>
      </div>
    </section>
  </div>
</template>

<style lang="scss" scoped>
.home {
  section {
    margin-bottom: 20rem;

    @include screen('small') {
      margin-bottom: 12rem;
    }
  }

  &__hero {
    max-width: 126rem;

    &-subtext {
      margin: 3rem 0 7rem;
      max-width: 87rem;

      @include screen('small') {
        margin-bottom: 5rem;
      }
    }
  }

  &__offers {
    &-list {
      display: flex;
      flex-wrap: wrap;
      justify-content: space-between;
      margin-top: 8rem;

      @include screen('small') {
        margin-top: 5rem;
      }
    }

    &-offer {
      width: 46%;
      margin-bottom: 10rem;

      .u-font-h3 {
        margin-bottom: 2.5rem;
        text-transform: uppercase;
      }

      &:nth-child(3),
      &:last-child {
        margin-bottom: 0;
      }

      @include screen('med-small') {
        $margin-bottom: 6rem;
        width: 100%;
        margin-bottom: $margin-bottom;

        &:nth-child(3) {
          margin-bottom: $margin-bottom;
        }
      }
    }
  }

  &__steps {
    &-list {
      display: flex;
      justify-content: space-between;
      flex-wrap: wrap;
      margin-top: 8rem;

      @include screen('small') {
        margin-top: 5rem;
      }
    }

    &-step {
      width: 28%;

      @include screen('med') {
        svg {
          height: fit-content;
        }

        &:first-child svg {
          width: 6rem;
        }

        &:nth-child(2) svg {
          width: 11rem;
        }

        &:last-child svg {
          width: 8rem;
        }
      }

      @include screen('med-small') {
        width: 100%;

        &:not(:last-child) {
          margin-bottom: 6rem;
        }
      }

      .u-font-h3 {
        margin: 2.5rem 0;
        text-transform: uppercase;
      }
    }
  }

  &__offers,
  &__steps {
    .u-font-h3 {
      @include screen('med-small') {
        margin-bottom: 1.6rem;
      }
    }
  }
}
</style>
