<template>
  <header>
  </header>

  <main>

    <div class="card w-96 bg-base-100 shadow-xl image-full" id="pagebox">
      <figure><img src="./assets/YolBilogo.png" alt="YolBi"/></figure>
      <div class="card-body">
        <h2 class="card-title">It's YolBi</h2>
        <p>But the website is still making</p>
        <div class="card-actions justify-end">
          <button @click="handleGithub" class="btn btn-primary">GitHub</button>
        </div>
        <div class="card-actions justify-end">
          <button @click="handleJoinNow" class="btn btn-primary">QQ Group</button>
        </div>
      </div>
    </div>

  </main>
</template>


<script>

export default {
  methods: {
    handleJoinNow() {
      console.log('clicked');
      window.open("https://qm.qq.com/cgi-bin/qm/qr?_wv=1027&k=n5HdIsm7at6tD7sSLrZv_lNDZp63M69a&authKey=DOC%2FqqaDW6Wd4ffIj2a%2F5KBNqPc6NQFnWSv1xQZK7lfglQ76LrbE8GGtELhdkILi&noverify=0&group_code=699481681");
    },
    handleGithub() {
      console.log('clicked');
      window.open("https://github.com/yapeteam");
    },
  }
}

</script>