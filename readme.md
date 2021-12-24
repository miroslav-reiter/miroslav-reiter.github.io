
<!DOCTYPE html>
<html>
  <head>
  <meta http-equiv="content-type" content="text/html; charset=utf-8">
  <meta name="author" content="Ing. Miroslav Reiter" />
  <meta lang="sk" content="IT Academy s.r.o." content="webvývojár, css, html, selektory, triedy, stylovanie" />
  
  <title>IT Academy - CSS v kocke</title>
  <link rel="stylesheet" href="styly.css" type="text/css" />
    
  </head>
  <body>
    <h1>IT Academy - CSS v kocke</h1>
    <h2>I. Komentáre / Comments</h2>
    
    <p><span style="font-weight:bold;">Použitie:</span> Poznámky pre vývojára, blokovanie funkcionality, metadáta.</p>
    <div style="border-left: 3px solid rgba(0, 0, 0, 0.102); padding: 0px 20px 0px 20px; ">

    <span class="spanBlock" style="color: #5d8e34; padding-bottom: 10px; font-weight:bold; ">Vzor:</span>      
          <div class="komentare">/* Toto je jednoriadkový komentár */</div>   <br />
    <span class="spanBlock" style="color: #5d8e34; padding-bottom: 10px; font-weight:bold; ">Vzor:</span>       
          <div class="komentare">/* Toto <br />
          je viacriadkovy <br />
          komentar */</div>                       
     </div>                             <br /><hr />
     
    <h2>II. Vlastnosti / Properties</h2>
    <p><span style="font-weight:bold;">Použitie:</span> Sú definované v rámci selektora tým, že definujú vlastnosť 
    a hodnotu.</p>
    <div style="border-left: 3px solid rgba(0, 0, 0, 0.102); padding: 0px 20px 0px 20px; ">
    
    <span class="spanBlock" style="color: #5d8e34; padding-bottom: 10px; font-weight:bold; ">Syntax:</span>      
      <div class="komentare">
        <span style="color:#B294BB;">selektor</span> { <br />
          &nbsp;&nbsp;&nbsp;<span style="color:#B58900;">vlasnosť:</span> 
          <span style="color:#DE935F;">hodnota;</span>    <br />
          }</div>   <br />
    <span class="spanBlock" style="color: #5d8e34; padding-bottom: 10px; font-weight:bold; ">Vzor:</span>       
      <div class="komentare">
        <span style="color:#B294BB;">h1</span> { <br />
          &nbsp;&nbsp;&nbsp;<span style="color:#B58900;">color:</span> 
          <span style="color:#DE935F;">red;</span>    <br />
          }</div>   <br /><br /><hr />
    </div>
        
    <h2>III. Viaceré vlastnosti / Many properties</h2>
    <div style="border-left: 3px solid rgba(0, 0, 0, 0.102); padding: 0px 20px 0px 20px; ">
    <span class="spanBlock" style="color: #5d8e34; padding-bottom: 10px; font-weight:bold; ">Vzor:</span>       
      <div class="komentare">
        <span style="color:#B294BB;">h1</span> { <br />
          &nbsp;&nbsp;&nbsp;<span style="color:#B58900;">color:</span> 
          <span style="color:#DE935F;">pink;</span>    <br />
                    &nbsp;&nbsp;&nbsp;<span style="color:#B58900;">font-size:</span> 
          <span style="color:#DE935F;"><span style="color:#B5BD68;">24</span>px;</span>    <br />
                    &nbsp;&nbsp;&nbsp;<span style="color:#B58900;">font-weight:</span> 
          <span style="color:#DE935F;">bold;</span>    <br />
                    &nbsp;&nbsp;&nbsp;<span style="color:#B58900;">border:</span> 
          <span style="color:#DE935F;"><span style="color:#B5BD68;">1</span>px solid black;</span>    <br /><br />
          &nbsp;&nbsp;&nbsp;/* Všetky nadpisy h1 budú veľké, tučné s rúžovou farbou a jednoduchým rámikom.*/<br />
          }</div><br />
          <div style="color: pink;font-size: 24px; font-weight: bold;border: 1px solid black;">
          Všetky nadpisy h1 budú veľké, tučné, rúžovou farbou a jednoduchým rámikom.</div>  <br /><hr />
    </div>
    
    <h2>IV. Padding</h2>
    <p><span style="font-weight:bold;">Použitie:</span> Je priestor medzi obsahom a okrajom 
    (vnútorný okraj). Pomocou CSS môžeme túto hodnotu posunúť bližšie alebo ďalej od obsahu.</p>
    <div style="border-left: 3px solid rgba(0, 0, 0, 0.102); padding: 0px 20px 0px 20px; ">
    <span class="spanBlock" style="color: #5d8e34; padding-bottom: 10px; font-weight:bold; ">Vzor:</span>       
      <div class="komentare">
        <span style="color:#B294BB;">#box</span> { <br />
          &nbsp;&nbsp;&nbsp;<span style="color:#B58900;">padding:</span> 
          <span style="color:#DE935F;"><span style="color:#B5BD68;">10</span>px;</span>    <br />
          }</div>   <br /><br /><hr />
    </div>
          
    <h2>V. Margin</h2>
    <p><span style="font-weight:bold;">Použitie:</span> Je priestor okolo prvku(vonkajší okraj). 
    Čím je vačší margin, tým je viac miesta medzi elementom a ďaľšími elementami okolo neho. 
    Takto môžeme nastaviť elementy k sebe bližšie, alebo ďalej od seba.</p>
    <div style="border-left: 3px solid rgba(0, 0, 0, 0.102); padding: 0px 20px 0px 20px; ">
    
    <span class="spanBlock" style="color: #5d8e34; padding-bottom: 10px; font-weight:bold; ">Vzor:</span>       
      <div class="komentare">
        <span style="color:#B294BB;">#box</span> { <br />
          &nbsp;&nbsp;&nbsp;<span style="color:#B58900;">margin:</span> 
          <span style="color:#DE935F;"><span style="color:#B5BD68;">10</span>px    
          <span style="color:#B5BD68;">5</span>px<span style="color:#B5BD68;"> 10</span>px
          <span style="color:#B5BD68;">5</span>px;</span><br />
          }</div>   <br /><br /><hr />
    </div>
          
    <h2>VI. Selektory</h2>
    <p><span style="font-weight:bold;">Použitie:</span> Používame v CSS, na štýlovanie(formatovanie) 
    vybraných častí HTML. Je možné použiť niekoľko rôznych metód na výber prvku.</p>
    <div style="border-left: 3px solid rgba(0, 0, 0, 0.102); padding: 0px 20px 0px 20px; ">
    
    <span class="spanBlock" style="color: #5d8e34; padding-bottom: 10px; font-weight:bold; ">Vzor:</span>       
      <div class="komentare">
        <span style="color:#B294BB;">selektor</span> { <br />
          &nbsp;&nbsp;&nbsp;<span style="color:#B58900;">pravidlo;</span><br /> 
          &nbsp;&nbsp;&nbsp;<span style="color:#B58900;">pravidlo;</span><br /> 
          &nbsp;&nbsp;&nbsp;<span style="color:#B58900;">pravidlo;</span><br /> 
          }</div>   <br /><br /><hr />
         </div>
          
    <h2>VII. Selektory elementov</h2>
    <p><span style="font-weight:bold;">Použitie:</span> Sú schopné vyberať elementy HTML 
    jednoducho podľa názvu elementu.</p>
    <div style="border-left: 3px solid rgba(0, 0, 0, 0.102); padding: 0px 20px 0px 20px; ">
    <span class="spanBlock" style="color: #5d8e34; padding-bottom: 10px; font-weight:bold; ">Vzor:</span>       
      <div class="komentare">
        <span style="color:#B294BB;">body</span> { <br />
          &nbsp;&nbsp;&nbsp;<span style="color:#B58900;">background-color:</span> 
          <span style="color:#DE935F;">333;    
          </span><br /> 
          }</div><br /><br />  
     <span class="spanBlock" style="color: #5d8e34; padding-bottom: 10px; font-weight:bold; ">Vzor:</span>       
      <div class="komentare">
        <span style="color:#B294BB;">h1</span> { <br />
          &nbsp;&nbsp;&nbsp;<span style="color:#B58900;">color:</span> 
          <span style="color:#DE935F;">blue;    
          </span><br />
          }</div>   <br /><br />
     <span class="spanBlock" style="color: #5d8e34; padding-bottom: 10px; font-weight:bold; ">Vzor:</span>       
      <div class="komentare">
        <span style="color:#B294BB;">a</span> { <br />
          &nbsp;&nbsp;&nbsp;<span style="color:#B58900;">text-underline:</span> 
          <span style="color:#DE935F;">none;    
          </span><br />
          }</div>                  
          <br /><br /><hr /> 
      </div>
          
    <h2>VIII. Selektory triedy / Class selectors</h2>
    <p><span style="font-weight:bold;">Použitie:</span> Môžete tiež vybrať HTML elementy 
    s názvom triedy. Na rozdiel od selektora ID, vyberá selektor triedy všetky elementy 
    so zodpovedajúcou triedou. </p>
    <div style="border-left: 3px solid rgba(0, 0, 0, 0.102); padding: 0px 20px 0px 20px; ">
    
    <span class="spanBlock" style="color: #5d8e34; padding-bottom: 10px; font-weight:bold; ">Vzor:</span>       
      <div class="komentare">
        <span style="color:#B294BB;">a<span style="color:#839496;">.link</span></span> { <br />
          &nbsp;&nbsp;&nbsp;<span style="color:#B58900;">font-size:</span> 
          <span style="color:#DE935F;"><span style="color:#B5BD68;">12</span>px;    
          </span><br /><br />  
          /* Vybrane HTML: &lt;a href="http://google.sk" class="link"&gt;,<br /> 
        &lt;a href="http://www.it-academy.sk" class="link academy"&gt; */ <br /> 
          }</div><br /><br />  
    <span class="spanBlock" style="color: #5d8e34; padding-bottom: 10px; font-weight:bold; ">Vzor:</span>       
      <div class="komentare">
        <span style="color:#839496;">.link</span> { <br />
          &nbsp;&nbsp;&nbsp;<span style="color:#B58900;">text-size:</span> 
          <span style="color:#DE935F;"><span style="color:#B5BD68;">1000</span>px;    
          </span><br /><br />  
          /* Vybrane HTML: &lt;a href="http://google.sk" class="link academy"&gt;,<br /> 
          &lt;span class="link"&gt; */ <br /> 
          }</div><br /><br /><hr />   
    </div>
                           
    <h2>IX. Selektory ID</h2>
    <p><span style="font-weight:bold;">Použitie:</span> Selektor ID sa označí iba jednu položku na 
    stránke. Ako termín "Identifikácia" naznačuje, bude ID selektor vyberať iba prvý prvok so 
    zodpovedajúcim ID.</p>
    <div style="border-left: 3px solid rgba(0, 0, 0, 0.102); padding: 0px 20px 0px 20px; ">
    
    <span class="spanBlock" style="color: #5d8e34; padding-bottom: 10px; font-weight:bold; ">Vzor:</span>       
      <div class="komentare">
        <span style="color:#B294BB;">#vecKtoruStylujem</span> { <br />
          &nbsp;&nbsp;&nbsp;<span style="color:#B58900;">color:</span> 
          <span style="color:#DE935F;">blue;    
          </span><br />
          &nbsp;&nbsp;&nbsp;<span style="color:#B58900;">font-size:</span> 
          <span style="color:#DE935F;"><span style="color:#B5BD68;">24</span>px;    
          </span><br /><br />  
          /* Vybrane HTML: &lt;span id="vecKtoruStylujem"&gt;*/<br /> 
          }</div><br /><br />  
    <span class="spanBlock" style="color: #5d8e34; padding-bottom: 10px; font-weight:bold; ">Vzor:</span>       
      <div class="komentare">
        <span style="color:#B294BB;">a<span style="color:#839496;">#itAcademy</span></span> { <br />
          &nbsp;&nbsp;&nbsp;<span style="color:#B58900;">color:</span> 
          <span style="color:#DE935F;">purple;    
          </span><br /><br />  
          /* Vybrane HTML: &lt;a href="http://www.it-academy.sk" id="itAcademy"&gt;*/<br />  
          }</div><br /><br /><hr />   
    </div>
                          
    <h2>X. Selektory atribútov / Attribute selectors</h2>
    <p><span style="font-weight:bold;">Použitie:</span> HTML elementom tiez mozno zvoliť ich atribúty.</p>
    <div style="border-left: 3px solid rgba(0, 0, 0, 0.102); padding: 0px 20px 0px 20px; ">
    
    <span class="spanBlock" style="color: #5d8e34; padding-bottom: 10px; font-weight:bold; ">Vzor:</span>       
      <div class="komentare">
        <span style="color:#B294BB;">a<span style="color:#CB4B16;">[href="http://www.it-academy.sk"]
        </span></span> { <br />
          &nbsp;&nbsp;&nbsp;<span style="color:#B58900;">color:</span> 
          <span style="color:#DE935F;">purple;    
          </span><br /><br />  
          /* Vybrane HTML: &lt;a href="http://www.it-academy.sk"&gt;*/<br /> 
          }</div><br /><br />  
    <span class="spanBlock" style="color: #5d8e34; padding-bottom: 10px; font-weight:bold; ">Vzor:</span>       
      <div class="komentare">
        <span style="color:#B294BB;">input<span style="color:#CB4B16;">[type="text"]
        </span></span> { <br />
          &nbsp;&nbsp;&nbsp;<span style="color:#B58900;">width:</span> 
          <span style="color:#DE935F;"><span style="color:#B5BD68;">100</span>px;    
          </span><br /><br />  
          /* Vybrane HTML: &lt;input type="text"&gt;*/<br /> 
          }</div><br /><br />  
    <span class="spanBlock" style="color: #5d8e34; padding-bottom: 10px; font-weight:bold; ">Vzor:</span>       
      <div class="komentare">
        <span style="color:#B294BB;">a<span style="color:#CB4B16;">[required]
        </span></span> { <br />
          &nbsp;&nbsp;&nbsp;<span style="color:#B58900;">border:</span> 
          <span style="color:#DE935F;"><span style="color:#B5BD68;">1</span>px red solid;    
          </span><br /><br />  
          /* Vybrane HTML: &lt;input type="text" required"&gt;*/<br /> 
          }</div><br /><br />  <hr /> 
     </div>
           
    <h2>XI. Detské selektory / child selectors</h2>
    <p><span style="font-weight:bold;">Použitie:</span> Môžete použiť viac selektorov na 
    získanie presne tých prvkov, ktoré chcete, pomocou rodičovského hniezdenia. Pomocou 
    symbolu (>) "väčšie ako", môžete vybrať iba priamych potomkov elementu(ísť dole len 
    jeden stupeň).</p>
    
    <div style="border-left: 3px solid rgba(0, 0, 0, 0.102); padding: 0px 20px 0px 20px; ">
    <span class="spanBlock" style="color: #5d8e34; padding-bottom: 10px; font-weight:bold; ">Vzor:</span>       
      <div class="komentare">
        <span style="color:#B294BB;">ul > li</span> { <br />
          &nbsp;&nbsp;&nbsp;<span style="color:#B58900;">display:</span> 
          <span style="color:#DE935F;">inline-block;    
          </span><br /><br />
          /* Vyberieme iba prvú úroveň položiek vo všetkých nečíslovaných zoznamoch */<br />  
          }</div><br /><br />  
    <span class="spanBlock" style="color: #5d8e34; padding-bottom: 10px; font-weight:bold; ">Vzor:</span>       
      <div class="komentare">
        <span style="color:#B294BB;">ul a</span> { <br />
          &nbsp;&nbsp;&nbsp;<span style="color:#B58900;">text-underline:</span> 
          <span style="color:#DE935F;">none;    
          </span><br /><br />
          /* Vyberie všetky kotvy, ktoré majú ako predka nečíslovaný zoznam. */<br />  
          }</div><br /><br /> 
    <span class="spanBlock" style="color: #5d8e34; padding-bottom: 10px; font-weight:bold; ">Vzor:</span>       
      <div class="komentare">
        <span style="color:#B294BB;">ul + span</span> { <br />
          &nbsp;&nbsp;&nbsp;<span style="color:#B58900;">display:</span> 
          <span style="color:#DE935F;">inline;    
          </span><br /><br />
          /* Vyberie len elementy SPAN, ktoré priamo nadväzujú na nečislovaný zoznam. */<br />  
          }</div><br /><br /> 
    <span class="spanBlock" style="color: #5d8e34; padding-bottom: 10px; font-weight:bold; ">Vzor:</span>       
      <div class="komentare">
        <span style="color:#B294BB;">a ~ h1</span> { <br />
          &nbsp;&nbsp;&nbsp;<span style="color:#B58900;">color:</span> 
          <span style="color:#DE935F;">blue;    
          </span><br /><br />
          /* Vyberie všetky elementy H1, ktoré sú v okolí kotvy. */<br />  
          }</div><br /><br /> <hr />
    </div>
          
    <h2>XII. Univerzálny selektor / Universal selector</h2>
    <p><span style="font-weight:bold;">Použitie:</span> Univerzálny selektor (*), môže byť 
    použitý pre výber všetky prvky v určitom rozsahu. Treba si, ale uvedomit, že tento 
    selektor je najglobalnejsi a mal by byť používaný šetrne.</p>
    
    <div style="border-left: 3px solid rgba(0, 0, 0, 0.102); padding: 0px 20px 0px 20px; ">
    <span class="spanBlock" style="color: #5d8e34; padding-bottom: 10px; font-weight:bold; ">Vzor:</span>       
      <div class="komentare">
        <span style="color:#B294BB;">*</span> { <br />
          &nbsp;&nbsp;&nbsp;<span style="color:#B58900;">background-color:</span> 
          <span style="color:#DE935F;">blue;    
          </span><br /><br />
          /* Vyberie všetky elementy HTML na stránke, nastavi im pozadie. */<br />  
          }</div><br /><br />  
    <span class="spanBlock" style="color: #5d8e34; padding-bottom: 10px; font-weight:bold; ">Vzor:</span>       
      <div class="komentare">
        <span style="color:#B294BB;">body *</span> { <br />
          &nbsp;&nbsp;&nbsp;<span style="color:#B58900;">color:</span> 
          <span style="color:#DE935F;">red;    
          </span><br /><br />
          /* Vyberie všetky deti/potomkov BODY a nastavím im červenú farbu písma. */<br />  
          }</div><br /><br /> 
    <span class="spanBlock" style="color: #5d8e34; padding-bottom: 10px; font-weight:bold; ">Vzor:</span>       
      <div class="komentare">
        <span style="color:#B294BB;">div > * </span> { <br />
          &nbsp;&nbsp;&nbsp;<span style="color:#B58900;">color:</span> 
          <span style="color:#DE935F;">red;    
          </span><br /><br />
          /* Vyberie všetky deti prvej úrovne všetkých tagov DIV na stránke. */<br />  
          }</div><br /><br /> <hr /> 
    </div>
          
    <h2>XIII. Selektory pseudotried / Pseudo class selectors</h2>
    <p><span style="font-weight:bold;">Použitie:</span> Možno nimi zúžiť výber pomocou 
    určitých špecifických pravidiel.</p>
    
    <div style="border-left: 3px solid rgba(0, 0, 0, 0.102); padding: 0px 20px 0px 20px; ">
    <span class="spanBlock" style="color: #5d8e34; padding-bottom: 10px; font-weight:bold; ">Vzor:</span>       
      <div class="komentare">
        <span style="color:#B294BB;">li:<span style="color:#CB4B16;">first-child</span></span> { <br />
          &nbsp;&nbsp;&nbsp;<span style="color:#B58900;">color:</span> 
          <span style="color:#DE935F;">red;    
          </span><br /><br />
              /* Vyberie len &lt;li&gt; elementy, ktoré nemajú žiadne prvky pred nimi. <br /> 
              &lt;ul&gt; <br /> 
                &nbsp;&nbsp;&nbsp;&lt;li&gt;Vybrané, budu červené&lt;/li&gt; <br /> 
                &nbsp;&nbsp;&nbsp;&lt;li&gt;Nevybrané&lt;/li&gt; <br /> 
                &nbsp;&nbsp;&nbsp;&lt;li&gt;Nevybrané&lt;/li&gt; <br /> 
              &lt;/ul&gt; <br />  
          }</div><br /><br />  
    <span class="spanBlock" style="color: #5d8e34; padding-bottom: 10px; font-weight:bold; ">Vzor:</span>       
      <div class="komentare">
        <span style="color:#B294BB;">li:<span style="color:#CB4B16;">last-child</span></span> { <br />
          &nbsp;&nbsp;&nbsp;<span style="color:#B58900;">color:</span> 
          <span style="color:#DE935F;">red;    
          </span><br /><br />
          /* Presný opak, len posledný element &lt;li&gt; bude červený. */<br />  
          }</div><br /><br /> 
        <span class="spanBlock" style="color: #5d8e34; padding-bottom: 10px; font-weight:bold; ">Vzor:</span>       
      <div class="komentare">
        <span style="color:#B294BB;">a:<span style="color:#CB4B16;">hover</span></span> { <br />
          &nbsp;&nbsp;&nbsp;<span style="color:#B58900;">text-decoration:</span> 
          <span style="color:#DE935F;">underline;    
          </span><br /><br />
              /* Všetky odkazy, ktoré budú oznacene myškou budu podčiarknuté. */ <br />  
          }</div><br /><br />  
    <span class="spanBlock" style="color: #5d8e34; padding-bottom: 10px; font-weight:bold; ">Vzor:</span>       
      <div class="komentare">
        <span style="color:#B294BB;">a:<span style="color:#CB4B16;">active</span></span> { <br />
          &nbsp;&nbsp;&nbsp;<span style="color:#B58900;">font-weight:</span> 
          <span style="color:#DE935F;">bold;    
          </span><br /><br />
          /* Zabezpeči, aby všetky odkazy boli tučné, zatiaľ čo používateľ na ne klikne. */<br />  
          }</div><br /><br /><hr />      
    </div>
  </body>
</html>
