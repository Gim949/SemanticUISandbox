<template>
  <div class="ui container">
    <h1>Wow aj</h1>
    <p>Semantic UI with Nuxt?</p>
    <a href="#">Probably yes but actually yes</a>
    <br />
    <br />

    <h1>Now for buttons</h1>
    <button>Big dumb</button>
    <button class="ui button">Big brain</button>
    <button class="ui button" tabindex="0">Notice me</button>

    <div class="ui divider"></div>

    <button class="ui primary button">Cool</button>
    <button class="ui secondary button">Second Cool</button>
    <div class="ui animated button">
      <div class="visible content">Thank you, next</div>
      <div class="hidden content">
        <i class="right arrow icon" />
      </div>
    </div>

    <div class="ui divider"></div>

    <p>Be sure to...</p>
    <div class="ui left labeled button">
      <a class="ui basic right pointing label">69m</a>
      <div class="ui button">
        <i class="heart icon" />
        Like
      </div>
    </div>
    <div class="ui labeled button">
      <div class="ui red button">
        <i class="fork icon" />
        Comment
      </div>
      <a class="ui basic red left pointing label">420</a>
    </div>

    <br />
    <br />

    <div class="ui buttons">
      <button class="ui button">One</button>
      <button class="ui button">Two</button>
      <button class="ui button active">Three</button>
    </div>

    <button class="ui disabled button">
      I cri
    </button>

    <button class="ui loading primary button">Wooo</button>

    <br />

    <button class="mini ui button">
      Mini
    </button>
    <button class="tiny ui button">
      Tiny
    </button>
    <button class="small ui button">
      Small
    </button>
    <button class="positive medium ui button">
      Medium
    </button>
    <button class="negative large ui button">
      Large
    </button>
    <button class="big ui button">
      Big
    </button>
    <button class="circular huge ui button">
      Huge
    </button>
    <button class="massive ui button">
      Massive
    </button>

    <div class="ui horizontal divider">Some stuff with dividers</div>

    <div class="ui placeholder segment">
      <div class="ui two column very relaxed stackable grid">
        <div class="column">
          <div class="ui form">
            <div class="field">
              <label>Username</label>
              <div class="ui left icon input">
                <input type="text" placeholder="Username">
                <i class="user icon"></i>
              </div>
            </div>
            <div class="field">
              <label>Password</label>
              <div class="ui left icon input">
                <input type="password">
                <i class="lock icon"></i>
              </div>
            </div>
            <div class="ui blue submit button">Login</div>
          </div>
        </div>
        <div class="middle aligned column">
          <div class="ui big button">
            <i class="signup icon"></i>
            Sign Up
          </div>
        </div>
      </div>
      <div class="ui vertical divider">
        Or
      </div>
    </div>

    <h3 class="ui block header">
      Wow this is getting big ( ͡° ͜ʖ ͡°)
    </h3>

    <div class="ui divider"></div>

    <div class="ui input">
      <input type="text" placeholder="Type here...">
    </div>
    <div class="ui input error">
      <input type="text" placeholder="Oh no it broke...">
    </div>
    <div class="ui input action">
      <input type="text" placeholder="Try again I guess...">
      <button class="ui button">Trying</button>
    </div>

    <div class="ui segment placeholder">
      <div class="line"></div>
      <div class="line"></div>
      <div class="line"></div>
      <div class="paragraph">
        <div class="line"></div>
        <div class="line"></div>
        <div class="line"></div>
        <div class="line"></div>
        <div class="line"></div>
        <div class="line"></div>
      </div>
    </div>

    <div class="ui message">
      <div class="header">
        Changes in Service
      </div>
      <p>We just updated our privacy policy here to better service our customers. We recommend reviewing the changes.</p>
      <p>This isn't actually true, I just began to copy and paste things</p>
    </div>
  </div>
</template>

<script>
export default {
  components: {
    
  }
}
</script>

<style>

</style>
