猴子吃香蕉可是掰成好几段来吃哦！

把一个数组arr按照指定的数组大小size分割成若干个数组块。
function chunk(arr, size) {
  // Break it up.
  var arr2=[];
  for(var i=0;i<arr.length;i=i+size){
    var arr1=arr.slice(i,i+size);
    arr2.push(arr1);
  }
  return arr2;
}

chunk(["a", "b", "c", "d"], 2);
