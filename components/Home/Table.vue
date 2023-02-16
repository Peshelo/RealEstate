<template>
  <table>
  <tr>
    <th>Location</th>
    <th>Hosted by</th>
    <th>Other</th>
    <th>Price</th>
    <th>Rating</th>
  </tr>
  <tr>
    <td>No 122 Lomagundi Emarald Harare</td>
    <td>ProperyMeme</td>
    <td>None</td>
    <td>$147/month</td>
    <td>4.5</td>
  </tr>
</table>
</template>

<script>
export default {

}
</script>

<style>
table{
    width:100%;
    background-color: white;
    border: 1px solid gray;
    border-radius: 10px;
    padding: 10px;
}
th{
    font:bold;
    background-color: var(--secondary);
    color:white;
}
tr{
    padding: 5px;
    margin: 1px 2px;
    text-align: start;
    border: 1px solid rgb(230, 230, 230);
}
tr:hover{
    background-color: rgb(228, 228, 228);
}
</style>