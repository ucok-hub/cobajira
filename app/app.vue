<template>
  <div class="container">
    <header>
      <img class="profile-pic" src="/favicon.ico" alt="Profile" />
      <h1>Rafif Nuraydin</h1>
      <p class="subtitle">Software Engineer | Web Developer</p>
    </header>
    <section>
      <h2>Tentang Saya</h2>
      <p>
        Lulusan Teknik Informatika dengan pengalaman dalam pengembangan web,
        pemrograman, dan teknologi terkini. Memiliki semangat belajar tinggi,
        teliti, dan mampu bekerja dalam tim maupun mandiri.
      </p>
    </section>
    <section>
      <h2>Pendidikan</h2>
      <ul>
        <li>
          <strong>Universitas XYZ</strong> <br />
          D4 Teknik Informatika, 2022 - 2026
        </li>
      </ul>
    </section>
    <section>
      function add(a,b){return a+b}
      <h2>Pengalaman</h2>
      <ul>
        <li>
          <strong>Magang Web Developer</strong> - PT ABC, 2025 <br />
          Mengembangkan aplikasi web menggunakan Vue.js dan Node.js.
        </li>
      </ul>
    </section>
    <section>
      <h2>Keahlian</h2>
      <ul class="skills">
        <li>JavaScript</li>
        <li>Vue.js</li>
        <li>Node.js</li>
        <li>HTML & CSS</li>
        <li>Git</li>
      </ul>
    </section>
    <footer>
      <p>Kontak: rafif@email.com | 0812-3456-7890</p>
    </footer>
  </div>
</template>

<style scoped>
.container {
  max-width: 600px;
  margin: 2rem auto;
  background: #fff;
  border-radius: 18px;
  box-shadow: 0 4px 24px rgba(0, 0, 0, 0.08);
  padding: 2rem 2.5rem;
  font-family: "Segoe UI", Arial, sans-serif;
}
header {
  text-align: center;
  margin-bottom: 2rem;
}
.profile-pic {
  width: 80px;
  height: 80px;
  border-radius: 50%;
  margin-bottom: 1rem;
  border: 2px solid #eee;
}
.subtitle {
  color: #888;
  font-size: 1.1rem;
  margin-top: -0.5rem;
}
h1,
h2 {
  color: #2a4d69;
}
section {
  margin-bottom: 1.5rem;
}
.skills {
  display: flex;
  flex-wrap: wrap;
  gap: 0.5rem;
  list-style: none;
  padding: 0;
}
.skills li {
  background: #f0f4f8;
  border-radius: 8px;
  padding: 0.4rem 1rem;
  font-size: 0.95rem;
}
footer {
  text-align: center;
  color: #aaa;
  font-size: 0.95rem;
  margin-top: 2rem;
}
</style>
