<template>
  <div class="team">
    <div class="team__profile">
      <div class="team__profile-details">
        <h2 class="u-font-h2">Dami</h2>
        <p>
          Damilola Marcus is a Co-founder and C.E.O of Design Capital. She is a
          serial entrepreneur and an award-winning designer who thrives at the
          intersection of design and business. Damilola is bullish team African
          founders and believes in the power of design to positively transform
          businesses. Outside of Design Capital, she is the Co-founder of one of
          Africa's leading design agencies,
          <a href="https://dadesign.studio/" target="_blank">
            Dá Design Studio.
          </a>
          She has helped design substantial brands for some of Africa's most
          exciting startups and companies. She is a member of the
          <a href="https://www.dandad.org/en/d-ad-impact/" target="_blank">
            D&AD impact council
          </a>
          - a small collection of senior figures from across the creative,
          investment, and social impact space who help award the world's most
          impactful creative ideas each year.
        </p>
        <p>
          When she's not working, she's a fabulous pet mum to Mushu and Lekki,
          reading, watching wacky t.v, binging docuseries, and sipping on Thai
          milk tea.
        </p>
      </div>
      <div class="team__profile-image">
        <img src="../assets/images/dami.jpg" />
      </div>
    </div>
    <div class="team__profile">
      <div class="team__profile-details">
        <h2 class="u-font-h2">Saratu</h2>
        <p>
          Saratu is the Co-Founder and C.L.O at Design Capital. She is a
          qualified lawyer with extensive experience in negotiating and
          structuring deals, advising clients on a broad range of transactions,
          and providing legal due diligence. She also holds certifications from
          the University of Oxford and American Society of Appraisers (ASA) on
          the valuation of intangible assets.
        </p>
        <p>
          Saratu is very passionate about supporting the growth of creativity
          and innovation in Africa, either through sharing her knowledge at
          <a href="https://projectip4u.wordpress.com/" target="_blank"
            >ProjectIP4U</a
          >
          or providing access to fundraising opportunities for founders, through
          the platform she co-founded,
          <a href="https://www.thefundplug.com/" target="_blank"
            >The Fund Plug</a
          >
        </p>
        <p>
          In her free time, she travels on random adventures and attempts to
          become a pro guitar player for the umpteenth time.
        </p>
      </div>
      <div class="team__profile-image">
        <img src="../assets/images/saratu.png" />
      </div>
    </div>
    <div class="team__profile">
      <div class="team__profile-details">
        <h2 class="u-font-h2">Oiza</h2>
        <p>
          Oiza Jagun is the Project Manager at Design Capital Ltd. She has a
          Bachelor's degree in Computer Science from the University of Lagos.
          She is also a Junior Partner at Dá Design Studio and the COO at
          Document Women. Oiza is an avid reader, a women's rights advocate and
          a lover of adventure and travel. Her professional experience spans
          various disciplines ranging from digital marketing to project
          management and performance and process improvement.
        </p>
        <p>
          She works to make sure deadlines are met, and everyone is kept on
          their toes. She owns a cat and two dogs.
        </p>
      </div>
      <div class="team__profile-image">
        <img src="../assets/images/oiza.jpg" />
      </div>
    </div>
    <div class="team__profile">
      <div class="team__profile-details">
        <h2 class="u-font-h2">Ted</h2>
        <p>
          Ted is the Co-Founder and C.P.O of Design Capital. Hoping between
          product and design leadership, Ted is passionate team design on the
          continent. Outside of Design Capital, he is Vice President of Design
          at Flutterwave where he leads a talented team that specializes in
          Product Design, User Research, Brand, and Marketing Design.
        </p>
        <p>
          He is a significant contributor to scaling the company from a little
          over 20,000 merchants to more than 1,000,000 merchants globally.
        </p>
        <p>
          He also leads products at
          <a href="https://archiving.substack.com/" target="_blank"
            >Archivi.ng</a
          >
          where they are archiving and digitizing Nigeria's history through the
          lens of the media, starting with newspapers.
        </p>
        <p>
          In his spare time, he collaborates with architects to design his dream
          home in Lagos and plays video games.
        </p>
      </div>
      <div class="team__profile-image">
        <img src="../assets/images/ted.jpg" />
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.team {
  .team__profile {
    display: flex;
    justify-content: space-between;
    margin-bottom: 20rem;

    @media screen and (max-width: 1280px) {
      margin-bottom: 14rem;
    }

    @media screen and (max-width: 1024px) {
      flex-wrap: wrap;
    }

    @include screen('small') {
      margin-bottom: 8rem;
    }

    &-details {
      .u-font-h2 {
        margin-bottom: 1.6rem;
      }

      p:not(:last-child) {
        margin-bottom: 3rem;

        @include screen('small') {
          margin-bottom: 2.4rem;
        }

        a {
          color: black;
        }
      }
    }

    &-image {
      overflow: hidden;
      --size: 56rem;
      width: var(--size);
      height: var(--size);
      background: rgb(206, 206, 206);
      flex-shrink: 0;
      margin-left: 15rem;
      border-radius: 1rem;

      @media screen and (max-width: 1280px) {
        --size: 52rem;
        margin-left: 8rem;
      }

      @media screen and (max-width: 1024px) {
        width: 100%;
        height: auto;
        margin-left: 0;
        margin-top: 4rem;
      }

      img {
        width: 100%;
        object-fit: cover;
        height: auto;
      }
    }
  }
}
</style>
