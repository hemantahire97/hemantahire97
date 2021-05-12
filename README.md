var data = "aaabbcccddd";
var n = data.length;
var result = "";

for (var i = 0; i < n; i++) {
  if (data[i] == data[i + 1]) {
    i = i + 2;
  } else {
    result = result + data[i];
  }
}
if (result == "") {
  console.log("Empty String");
} else {
  console.log(result);
}
