<html>
<header>
<!-- Ajax -->
<!-- <script src="http://ajax.googleapis.com/ajax/libs/jquery/1.11.2/jquery.min.js"></script> -->
<!-- Bootstrap -->
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.min.js" integrity="sha384-QJHtvGhmr9XOIpI6YVutG+2QOK9T+ZnN4kzFN1RtK3zEFEIsxhlmWl5/YESvpZ13" crossorigin="anonymous"></script>
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p" crossorigin="anonymous"></script>

</header>

<h3 id = "activeMiners"> </h3>
<h3 id = "miningPower"> </h3>


<table id="nftHolders" class="table table-hover table-dark">
  <thead>
    <tr>
      <th scope="col">Top Holders</th>
      <th scope="col">Wallets</th>
      <th scope="col">Assets</th>
    </tr>
  </thead>
  <tbody> 
  </tbody>
</table>



<script>
miningPower = 0;
publicAssets = 0;


const dripAPI ="./data.json";
fetch(dripAPI).then(function (res) {
  return res.json()
}).then(function (data) {
  let list = data.data;

for(let x = list.payload.length-1; x >= 0; x--){  

if (list.payload[x].minecraftUUID == '18d666be0c504b7a94b7478494e345dc'){
  // Get the amount of miners from the neftyblocksd account.
miningPower = list.payload[x].dripPerHour;
}}
}).catch(function (error) {
  console.log(error);

})



const minerAPI ="https://wax.api.atomicassets.io/atomicassets/v1/accounts?collection_name=minerstonksz&template_id=516244&page=1&limit=250&order=desc";
fetch(minerAPI).then(function (res) {
  return res.json()
}).then(function (data) {
  let list = data.data;
  

for(let i = list.length-1; i >= 0; i--){  


  // Check for the account neftyblocksd
if (list[i].account == 'neftyblocksd'){
  // Get the amount of miners from the neftyblocksd account.
neftyMiners = list[i].assets;

}
else{
  neftyMiners = 0;
}

  // Check for the account neftyblocksd
  if (list[i].account == 'upliftminers'){
  // Get the amount of miners from the neftyblocksd account.
  upliftMiners = list[i].assets;
}
else{
  upliftMiners = 0;
}


// Select the right Table and push the data into this table. 
  var table = document.getElementById("nftHolders");
  var row = table.insertRow(1);
  var cell1 = row.insertCell(0);
  var cell2 = row.insertCell(1);
  var cell3 = row.insertCell(1);

  cell1.innerHTML = [i];
  cell2.innerHTML = list[i].assets;
  cell3.innerHTML = list[i].account;


  publicAssets += parseInt(list[i].assets);


}
// Calculations 
totalAssets = publicAssets - neftyMiners - upliftMiners;
dripMiner = miningPower / totalAssets;


document.getElementById("activeMiners").innerHTML = "Active miners " + totalAssets;
document.getElementById("miningPower").innerHTML = "Mining Power per asset " + Math.floor(dripMiner);
console.log(dripMiner);




}).catch(function (error) {
  console.log(error);

})



</script>




