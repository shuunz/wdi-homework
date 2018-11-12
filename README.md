# wdi-homework
<script>

var snakewaterMontana = {
  paleontologist: "Dr. Alan Grant",
  depth: "10 meters",
  specimen: "Velociraptor"
}

var guestOfHonor = snakewaterMontana.paleontologist;
var cleverGirl =snakewaterMontana.specimen;

 var nicaragua = {
    depth: "200 meters",
    annualBudget: 1500000,
    specimens: [
      "Tyrannosaurus Rex",
      "Stegosaurous",
      "Triceratops",
      "Velociraptor"
    ]
  }

var nicaraguanSpecimens =nicaragua.specimens;
console.log(nicaraguanSpecimens);

var favoriteSpecimen =nicaraguanSpecimens[1];
console.log(favoriteSpecimen);
  nicaragua.annualBudget+250000;
  

hammondsMines = {
  buenosAires: {
    depth: "400 meters",
    annualBudget: 1000000,
    specimens: [
      "Dilophosaurus",
      "Brachiosaurus"
    ]
  },
  mexico: {
    depth: "350 meters",
    annualBudget: 900000,
    specimens: [
      "Gallimimus",
      "Parasaurolophus"
    ]
  }
}
/*part 3*/

var mexicoDepth =hammondsMines.mexico['depth'];
var buenosBudget = hammondsMines.buenosAires['annualBudget'];
console.log(mexicoDepth);
console.log(buenosBudget);
hammondsMines.buenosAires.specimens['Dilophosaurus'];


/*hammondsMines =Array.prototype.push.apply(hammondsMines,nicaragua);*/
/*hammondsMines,push(nicaragua)*/
hammondsMines.nicaragua=nicaragua;
console.log(hammondsMines);

var nicaraguaBudget =nicaragua.annualBudget;
var buenosAiresBudget =hammondsMines.buenosAires['annualBudget'];
var mexicoBudget =hammondsMines.mexico['annualBudget'];

console.log(nicaraguaBudget);
console.log(buenosAiresBudget);
console.log(mexicoBudget);
var totalOfBudgets =nicaraguaBudget+buenosBudget+mexicoBudget;
console.log(totalOfBudgets);
console.log(hammondsMines.mexico.specimens[1]);

  </script>
