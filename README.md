<h1 id="title">처음 글자</h1>
<button id="btn">바꾸기</button>

 
<style>
  h1 { color: #D1E0FC; }
</style>
 
<script>
  document.querySelector('#btn').addEventListener('click', function () {
    document.querySelector('#title').textContent = '바뀐 글자!';
  });
</script>
