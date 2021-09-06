function date() {
  var date = new Date();
  var cikl = true;
  while (cikl) {
    var x  = prompt("Gri jam@");
    var y = prompt("Gri ropen");
    if ((x.length || y.length) > 2 ||  (x > 24 || y > 60) || (x < 0 || y < 0 ) || x == ""  || y == "") {
      alert("greq chisht jam ev chish rope");
    } else {
      cikl = true;
      date.setHours(x);
      date.setMinutes(y);
      alert("Jam@ " + date.getHours() + ":" + date.getMinutes());
      break
    }
  }
}

date();
