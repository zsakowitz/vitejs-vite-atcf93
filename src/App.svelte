<script>
  let age = 14

  function die() {
    age = 0
  }

  function getOlder() {
    age += 1
  }
</script>

<h1>Hello</h1>

<p>
  You are {age} years old.
</p>

<button on:click={die}>Die</button>

<button on:click={getOlder}>Get older</button>

<button on:click={() => age += 10} on:dblclick={() => age += 1000}>Get much older</button>

<style>
  h1 {
    background: red;
    color: orange;
  }
</style>
