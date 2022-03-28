var num=1;
function Taidulieubandau()
{
  var sodong = localStorage.length;
  for(let i=0;i<sodong;i++)
  {
    var tbl = document.getElementById("list");
    var id= localStorage.key(i);
    var row = tbl.insertRow(num);
    var cell1= row.insertCell(0);
    var cell2= row.insertCell(1);
    var cell3= row.insertCell(2);
    var cell4= row.insertCell(3);
    var cell5= row.insertCell(4);
    num++;
    var dulieu = JSON.parse(localStorage.getItem(id));
    cell1.innerHTML = dulieu.diadiem;
    cell2.innerHTML= dulieu.gia;
    cell3.innerHTML= dulieu.ngay;
    cell4.innerHTML= dulieu.ht;
    cell1.setAttribute("class","border border-dark text-center");
    cell2.setAttribute("class","border border-dark");
    cell3.setAttribute("class","border border-dark");
    cell4.setAttribute("class","border border-dark");
    cell5.setAttribute("class","border border-dark text-center");
    row.setAttribute("id",id);   
    var nutxoa=" <img src='../IMG/icons8-delete-30.png'";
    nutxoa+=" onclick=\"Xoadong(\'"+id+"\')\"/>";
    var nutsua="<img src='../IMG/icons8-edit-30.png'";
    nutsua+=" onclick=\"Suadong(\'"+id+"\')\" data-toggle=\"modal\" data-target=\"#myModal\" />";
    cell5.innerHTML=nutsua+" "+nutxoa;   
  }
}
function validate()
{
        var tbl = document.getElementById("list");
        var row = tbl.insertRow(num);
        var cell1= row.insertCell(0);
        var cell2=row.insertCell(1);
        var cell3=row.insertCell(2);
        var cell4=row.insertCell(3);
        var cell5=row.insertCell(4);
        cell1.innerHTML=document.getElementById("diadiem").value;
        cell2.innerHTML=document.getElementById("gia").value;
        cell3.innerHTML=document.getElementById("ngay").value;
        cell4.innerHTML=document.getElementById("ht").value;
        num++;
        row.setAttribute("id","tr_"+num);
        var nutxoa="<input type='button' class='btn btn-danger' value='Xóa'";
        nutxoa+="onclick=\"Xoadong(\'tr_"+num+"\')\"/>";
        var nutsua="<input type='button' class='btn btn-warning' data-toggle='modal' data-target='#myModal'  value='Sửa'" ;
        var num
        nutsua+="onclick=\"Suadong(\'tr_"+num+"\')\"/>";
        cell5.innerHTML=nutsua+" "+nutxoa;
        cell1.setAttribute("class","border boder-dark");
        cell2.setAttribute("class","border boder-dark");
        cell3.setAttribute("class","border boder-dark");
        cell4.setAttribute("class","border boder-dark");
        cell5.setAttribute("class","border boder-dark text-center");
        localStorage.setItem(id,JSON.stringify({"diadiem":cell1.innerHTML,"gia":cell2.innerHTML,
    "ngay":cell3.innerHTML,"ht":cell4.innerHTML}));
    num++;
}
function Xoadong(dong)
{
    if(confirm("bạn có chắc chắn xóa chứ?"))
    {
        var xoadong=document.getElementById(dong);
        xoadong.remove();
        num--;
    }
}
function Suadong(dong)
{
    document.getElementById("btnluu").setAttribute("style","visibility:visible");
    document.getElementById("btnbo").setAttribute("style","visibility:visible");
    var dulieu = document.getElementById(dong);
    document.getElementById("diadiem").value=dulieu.cells.item(0).innerHTML;
    document.getElementById("gia").value=dulieu.cells.item(1).innerHTML;
    document.getElementById("ngay").value=dulieu.cells.item(2).innerHTML;
    document.getElementById("btnthem").setAttribute("style","visibility:hidden");
    document.getElementById("btnluu").textContent = dong;                                                                                                                                                               
    document.getElementById("ht").value=dulieu.cells.item(3).innerHTML;
}
function skip()
{
    document.getElementById("btnluu").setAttribute("style","visibility:hidden")
    document.getElementById("btnbo").setAttribute("style","visibility:hidden")
    document.getElementById("btnthem").setAttribute("style","visibility:visible")
    document.getElementById("diadiem").value="";
    document.getElementById("gia").value="";
    document.getElementById("ngay").value="";
    document.getElementById("ht").value=""
}
function capnhat()
{

        var dong = document.getElementById("btnluu").textContent;
        var dulieu = document.getElementById(dong);
        dulieu.cells.item(0).innerHTML=document.getElementById("diadiem").value;
        dulieu.cells.item(1).innerHTML=document.getElementById("gia").value;
        dulieu.cells.item(2).innerHTML=document.getElementById("ngay").value;
        dulieu.cells.item(3).innerHTML=document.getElementById("ht").value;
        skip();
        var diadiem=document.getElementById("diadiem").value;
    var gia=document.getElementById("gia").value;   
    var ngay=document.getElementById("ngay").value;   
    var ht=document.getElementById("ht").value;
    localStorage.setItem(dong,JSON.stringify({"diadiem":diadiem,
    "gia":gia,"ngay":ngay,"ht":ht}));
    skip();
}

