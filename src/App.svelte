<script>
  let age
  age = 14

  function onClick() {
    age = age + 1
  }

  function reduceTheAge() {
    age -= 1
  }
</script>

<h1>Hello</h1>

<p>
  I have a dog. {age}
</p>

<h2>This is level 2 heading.</h2>

<button on:click={reduceTheAge}>Reduce the age</button>

<button on:click={onClick}>Increase the age</button>

<style>
  h1 {
    background: red;
    color: orange;
  }
</style>
