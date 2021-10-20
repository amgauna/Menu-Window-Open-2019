# menu-window
Exemplo de menu window.open()

<code>
<menu type="context" id="mymenu" class="navigation" style="word-spacing:20px; width:100%; height:auto; 
      margin:0px; padding:10px; cursor:pointer; background-color: #ffffff !important;">

    <menuitem label="#Home">
    <a href="#" onclick="window.open('home.html');">	
    <span class="glyphicon glyphicon-home">Home</span> </a> </menuitem> 
	
	<menuitem label="#Sobre" target="_self">
    <a href="#" onclick="window.open('sobre.html');">		
	<span class="glyphicon glyphicon-briefcase" target="_self">Sobre</span> </a> </menuitem>
	
	<menuitem label="#Serviços" target="_self">
    <a href="#" onclick="window.open('servicos.html');">		
	<span class="glyphicon glyphicon-usd">Serviços</span> </a> </menuitem> 
	
	<menuitem label="#Contato"  target="_self">
	<a href="#" onclick="window.open('contato.html');">  
	<span class="glyphicon glyphicon-th-large">Contato</span> </a> </menuitem> 
</menu>
</code>
