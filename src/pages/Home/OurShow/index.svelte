<script type="ts">
  import posterUrl from './poster.jpg';
</script>

<style>
  .t-section {
    background: grey;
  }

  .t-poster {
    background: transparent;
    border: none;
  }

  .t-blurb,
  .t-info {
    background-color: rgba(255, 255, 255, 0.95);
  }

  img {
    margin: 0 auto;
  }

  ul {
    list-style: none;
  }

  .list-group-item {
    background-color: transparent;
    border: none;
  }

  @media (min-width: 1200px) {
    .card-deck {
      width: 75%;
    }
  }
</style>

<div class="t-section t-pad-section d-flex flex-column align-items-center px-3">
  <h2>Our Show</h2>
  <div class="card-deck">
    <div class="t-poster card pt-3"><img class="img-fluid" src={posterUrl} alt="Back in the Naughty Chair" /></div>
    <div class="t-blurb card">
      <div class="card-body">
        <p>Following their 2017 hit show, Boganocracy, local comedy troupe The Mooks are Back in the Naughty Chair for 2019.</p>
        <p>
          The Mooks, consisting of Chris Cole, Greg Tantala and Lara Robertson, first met back in the time of knights and dames during Australia’s Tony Abbot
          years. Before that time, Chris had slummed around Melbourne bars doing various musical-comedy shows, drawing the attention of Greg who quickly bonded
          with Chris about their shared love of low-brow satire. Both soon began performing comedy and met Lara who agreed to perform with them after only seven
          months of begging, and thus The Mooks were born.
        </p>
        <p>
          The Mooks’ first Melbourne International Comedy Festival show was praised as an hilarious satire which showcased not only their joke writing chops,
          but also their flair for musical comedy. Their latest show, Back in the Naughty Chair, brings together their love of absurd comedy and silly songs,
          where they take on everything from the art of seduction in a social media landscape, being judged by Netflix’s algorithm and when you can take an '80s
          obsession a bit too far.
        </p>
      </div>
    </div>
    <div class="t-info card">
      <div class="card-body">
        <ul class="list-group">
          <li class="list-group-item p-0">
            <h4>Venue:</h4>
            <p><a href="http://www.redbetty.com.au" target="_blank">Red Betty</a></p>
            <p>
              <a
                href="https://www.google.com.au/maps/place/Red+Betty/@-37.7560066,144.9635621,15z/data=!4m5!3m4!1s0x0:0x597db8e5833ab226!8m2!3d-37.7560066!4d144.9635621"
                target="_blank">Rear of 859a Sydney Road (entry via Cozens st and Houdini Lane)</a>
            </p>
            <p>Venue is 18+</p>
          </li>
          <li class="list-group-item p-0">
            <h4>Dates:</h4>
            <p class="m-0">April</p>
            <p class="m-0">Thur 4 - Fri 5,</p>
            <p class="m-0">Tue 9 - Thur 11,</p>
            <p class="">Tue 16 - Thur 18</p>
          </li>
          <li class="list-group-item p-0">
            <h4>Time:</h4>
            <p>8pm</p>
          </li>
          <li class="list-group-item p-0">
            <h4>Tickets:</h4>
            <p>$15 - 25</p>
          </li>
          <li class="list-group-item p-0">
            <h4>Bookings:</h4>
            <p><a href="https://www.comedyfestival.com.au/2019/shows/the-mooks-back-to-the-naughty-chair" target="_blank">www.comedyfestival.com.au</a></p>
            <p><a href="https://www.trybooking.com/445931" target="_blank">www.trybooking.com</a></p>
            <p>or at the venue</p>
          </li>
        </ul>
      </div>
    </div>
  </div>
</div>
