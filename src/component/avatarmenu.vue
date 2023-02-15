<template>
    <div style="position: relative; top: 100px;" id="avatar">
    <div id="tombol">
  <button class="btn btn-light" type="button" data-bs-toggle="collapse" data-bs-target="#collapseExample" aria-expanded="false" aria-controls="collapseExample">
    open status <span class="badge bg-danger">1</span>
  </button>
</div>
<div id="bawah">
<div class="collapse" id="collapseExample">
  <div class="card card-body" style="color: black; background-color: black;">
  <table id="tabel">
    <tr>
        <th>Name</th>
        <th>Capability</th>
    </tr>
    <tr>
        <td><span><img src="../img/html.png" alt="html"></span><p style="color: black;">HTML</p></td>
        <td>Advance</td>
    </tr>
    <tr>
        <td><span><img src="../img/css.png" alt="css"></span><p style="color: black;">CSS</p></td>
        <td>Advance</td>
    </tr>
    <tr>
        <td><span><img src="../img/js.png" alt="js"></span><p style="color: black;">JavaScript</p></td>
        <td>Intermediate</td>
    </tr>
    <tr>
        <td><span><img src="../img/react-2.png" alt="react"></span><p style="color: black;">React</p></td>
        <td>Intermediate</td>
    </tr>
    <tr>
        <td><span><img src="../img/vue.png" alt="vue"></span><p style="color: black;">Vue</p></td>
        <td>Advance</td>
    </tr>
    <tr>
        <td><span><img src="../img/bootstrap.png" alt="bootstrap"></span><p style="color: black;">Bootstrap</p></td>
        <td>Intermediate</td>
    </tr>
    <tr>
        <td><span><img src="../img/sass.png" alt="">sass</span><p style="color: black;">SASS</p></td>
        <td>Advance</td>
    </tr>

  </table>
</div>
</div>
</div>
    </div>
</template>

<script>
    export default {
        
    }
</script>

<style lang="scss" scoped>
#avatar{
    #tombol{
        position: relative;
        display: flex;
        align-items: center;
        justify-content: center;
        gap: 20px;
    }
}
.card {
    position: relative;
    background-color: whitesmoke;
}

#collapseExample{
    top: 10px;
    position: relative;
    justify-content: center;
    align-items: center;
    width: 100%;
}

#bawah{
    display: flex;
    justify-content: center;
    align-items: center;
}
#tabel{
    width: 150px;
  font-family: Arial, Helvetica, sans-serif;
  border-collapse: collapse;
  width: 100%;
}

td,th{
    color: black;
    border: 1px solid #ddd;
  padding: 8px;
}
th {
  padding-top: 12px;
  padding-bottom: 12px;
  text-align: left;
  background-color:black;
  color: white;
}

tr:nth-child(even){
    background-color:grey;}
tr:nth-child(odd){background-color:rgb(54, 68, 54)}
tr:hover {background-color: lightblue}

</style>


<style>
   
@media only screen and (max-width: 768px)  {
    tr td:nth-child(odd){
        color: white;
    }
    td>p{
        display: none;
    }
}
</style>


