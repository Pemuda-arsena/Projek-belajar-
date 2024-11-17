// ahambuger menu
const nb=document.querySelector('.navbar-menu');
document.querySelector('#hamburger-menu').onclick = (a) => {
  nb.classList.toggle('active');
  hm.focus();
  a.preventDefault();
};

// tombol pncarian
const searchform= document.querySelector('.search-form');
const searchbox= document.querySelector('#search-box');
document.querySelector('#search-botom').onclick = (e) => {
  searchform.classList.toggle('active');
  sb.focus();
  e.preventDefault();
};

// Menutup di luar element
const hm =document.querySelector('#hamburger-menu');

const sb =document.querySelector('#search-botom');

document.addEventListener('click', function(e) {
  if (!hm.contains(e.target) && !nb.contains(e.target)) {
    nb.classList.remove('active');
  }
    if (!sb.contains(e.target) && !searchform.contains(e.target)) {
    searchform.classList.remove('active');
  }
document.querySelector(".instagrampembina").addEventListener("click", function (pembina) {
  pembina.preventDefault(); // Mencegah perilaku default (navigasi keluar halaman)
  
  // Logika atau aksi yang Anda inginkan, misalnya:
  console.log("Ikon Instagram diklik, tetap di halaman ini.");
  // Jika ingin membuka Instagram dalam tab baru:
  window.open("https://www.instagram.com/accounts/onetap/?next=%2F", "_blank");
});
document.querySelector(".instagramketua").addEventListener("click", function (ketua) {
  ketua.preventDefault(); // Mencegah perilaku default (navigasi keluar halaman)
  
  // Logika atau aksi yang Anda inginkan, misalnya:
  console.log("Ikon Instagram diklik, tetap di halaman ini.");
  // Jika ingin membuka Instagram dalam tab baru:
  window.open("https://www.instagram.com/accounts/onetap/?next=%2F", "_blank");
});
document.querySelector(".instagramwakilketua").addEventListener("click", function (wakil) {
  wakil.preventDefault(); // Mencegah perilaku default (navigasi keluar halaman)
  
  // Logika atau aksi yang Anda inginkan, misalnya:
  console.log("Ikon Instagram diklik, tetap di halaman ini.");
  // Jika ingin membuka Instagram dalam tab baru:
  window.open("https://www.instagram.com/accounts/onetap/?next=%2F", "_blank");
});
document.querySelector(".instagramsekretaris").addEventListener("click", function (sk) {
  sk.preventDefault(); 
  
  console.log("Ikon Instagram diklik, tetap di halaman ini.");

  window.open("https://www.instagram.com/accounts/onetap/?next=%2F", "_blank");
});
document.querySelector(".instagrambendahara").addEventListener("click", function (bdr) {
  bdr.preventDefault(); 
  
  console.log("Ikon Instagram diklik, tetap di halaman ini.");

  window.open("https://www.instagram.com/accounts/onetap/?next=%2F", "_blank");
});
document.querySelector(".instagrambimbing").addEventListener("click", function (bb) {
  bb.preventDefault(); 
  
  console.log("Ikon Instagram diklik, tetap di halaman ini.");

  window.open("https://www.instagram.com/accounts/onetap/?next=%2F", "_blank");
});
document.querySelector(".instagrampetugas").addEventListener("click", function (tig) {
  tig.preventDefault();
  console.log("Ikon Instagram diklik, tetap di halaman ini.");
  window.open("https://www.instagram.com/direct/t/17847174848968054", "_blank");

});
document.querySelector(".instagramhero").addEventListener("click", function (hero) {
  hero.preventDefault();
  console.log("Ikon Instagram diklik, tetap di halaman ini.");
  window.open("https://www.instagram.com/direct/t/17847174848968054", "_blank");

});
document.querySelector(".instagramfooter").addEventListener("click", function (foot) {
  foot.preventDefault();
  console.log("Ikon Instagram diklik, tetap di halaman ini.");
  window.open("https://www.instagram.com/direct/t/17847174848968054", "_blank");

});
window.addEventListener('load', function () {
            const welcomeElement = document.getElementById('welcome');
            setTimeout(() => {
                welcomeElement.classList.add('hidden');
            }, 3000); // Waktu 3 detik sebelum menghilang
        });

});
