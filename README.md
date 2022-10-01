<!DOCTYPE html>
<html lang="en">
</head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" type="text/css" href="index.css" media="screen">
    <title>Cadastro</title>
<head>
<body>

<div class="Campo">
    <h1 id="titulo">Registration  DEVs</h1>
    <p id="subtitulo">Complete your informations</p>
    <br>
</div class="Campo">

<form>
    <fieldset class="Group">
        <div class="campo">
           <label for="Name"><strong>Name</strong></label>
           <input type="text" name="nome" id="nome" required>
        </div class="campo">


        <div class="campo">
            <label for="Last name"><strong>Last Name</strong></label>
            <input type="text" name="Last name" id="Last name" required>
        </div class="Campo">

        <div class="campo">
            <label for="email"><strong>Email</strong></label>
            <input type="email" name="email" id="email" required>
        </div class="campo">
    </fieldset class="Group">


    <div class="campo">
     <Label><strong>Which Side of application you develop</strong></Label>  
     <label>
        <input type="radio" name="devweb" value="Front-End" checked>Front-End
        <input type="radio" name="devweb" value="Back-End">Back-End
        <input type="radio" name="devweb" value="Full-stack">Full-stack
     </label>
    </div class="campo">
<br>
    <div class="campo">
       <label><strong>Seniority</strong></label>
       <select id="Senioridade">
        <option selected disabled value="">Choice</option>
        <option>Junior</option>
        <option>Full</option>
        <option>Sênior</option>
       </select>
    </div class="campo">

<fieldset class="Group">
    <div id="check">
        <label><strong>Select the technologies you use</strong></label><br><br>
        <input type="checkbox" id="technology1" name="tecnology1" value="HTML">
        <strong><label for="technology1">HTML</label><strong>
        <input type="checkbox" id="technology2" name="technology2" value="CSS">
        <label for="technology2">CSS</label></strong>
        <input type="checkbox" id="tecnology3" name="technology3" value="Javascript">
        <label for="technology3">Javascript</label><strong>
        <input type="checkbox" id="technology4" name="technology4" value="PHP">
        <label for="technology4">PHP</label>
        <input type="checkbox" id="technology5" name="technology5" value="C#">
        <label for="tecnology5">C#</label>
        <input type="checkbox" id="tecnology6" name="tecnhnology6" value="Python">
        <label for="tecnology6">Python</label>
        <input type="checkbox" id="technology7" name="technology7" value="Java">
        <label for="technology7">Java</label>
    </div class="campo">
</fieldset class="Group">

<div class="campo">
    <br>
    <label><strong>tell us a little about your experience</strong></label>
    <textarea row="6" style="width:26em;" id="experiência" name="experiência"></textarea>
</div class="campo">

<button class="Button" type="submit">Concluido!!</button>

</form>

</body>
</html>


*{
   margin: 0;
   padding: 0;
}

#titulo{
    font-family:sans-serif;
    color: #380b61;
    margin-left:7%;
}

#subtitulo{
    font-family:sans-serif;
    color: #380b61;
    margin-left:10%;
}

fieldset{
    border:0;
}

body{
   background-color:#F0f8ff;
   font-family: sans-serif;
   font-size: 1em;
   color:#59429d;
   margin-left:36%;
   margin-top: 2%;
   justify-content: center;
}

input, select, textarea, button{
    border-radius: 4px;
}

.campo{
    margin-bottom: 1em;
}

.campo label{
    margin-bottom: 0.5em;
    color:rgba(89, 66, 157);
    display:block;
}

fieldset.grupo .campo{
    float:left;
    margin-right: 1em;
}

.campo input[type="text"], .campo input[type="email"], .campo select, .campo textarea{
    padding: 0.2em;
    border: 1px solid #59429d;
    box-shadow: 2px, 2px, 2px rgb(0,0,0,0.2)
    display:block;
}

.campo select option{
    padding-right:1em;
} 

.campo input:focus, .campo select:focus, .campo textarea:focus{
    background: #e0e0f7;
}

.botão {
    font-size:1.2em;
    background: #59429d;
    margin-bottom: 1em;
    color:#ffffff;
    padding:0.2em 0.6em;
    box-shadow: 2px 2px 2px; color: rgba(0,0,0,0.2);
    text-shadow: 1px, 1px, 1px, 1px; color:rgba(0,0,0,0.3);
    position:relative;
    top:90%;
    left:3%;
    margin-right: -43%;
    transform:translate(-50%, -50%);
}

.botão:hover{
background:#f0f6ff;
box-shadow: inset 2px, 2px, 2px  rgba(0,0,0,0.3);
box-shadow: none;
}

#check{
    display: inline-block;
}
