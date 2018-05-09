---
layout : page
title : Segunda Vuelta 2016
no_bio : true  
tags :  
  - Data
  - d3
page_scripts:
  - segunda-vuelta/script.js
page_external_script :
  - d3js.org/d3.v3.min.js
  - d3js.org/topojson.v1.min.js
css : segunda-vuelta/style.css
---
<div class="row h-100">
        <div id="svg-container" class="col-sm-6">
            <svg></svg>
        </div>
        <div class="col-sm-6" id="summary-container">
            <h2 class="display-4" id="nombre">Lima</h2>
            <h5 class="display-5" id="departamento">Lima</h5>
            <table class="table table-striped">
                <thead>
                <tr>
                    <th scope="col">Agrupacion</th>
                    <th scope="col">Votos</th>
                    <th scope="col">% Votos validos</th>
                    <!--<th scope="col">% Votantes</th>-->
                </tr>
                </thead>
                <tbody>
                <tr>
                    <th scope="row">Peruanos por el Kambio</th>
                    <td id="ppk" class="text-center">0</td>
                    <td id="per-ppk" class="text-center">0</td>
                    <!--<td id="per-ppk-abs">0</td>-->
                </tr>
                <tr>
                    <th scope="row">Fuerza Popular</th>
                    <td id="fp" class="text-center">0</td>
                    <td id="per-fp" class="text-center">0</td>
                    <!--<td id="per-fp-abs">0</td>-->
                </tr>
                <tr>
                    <th scope="row">Nulos</th>
                    <td id="null" class="text-center">0</td>
                    <td id="per-null" class="text-center">0</td>
                    <!--<td id="per-null-abs">0</td>-->
                </tr>
                <tr>
                    <th scope="row">Impugnados</th>
                    <td id="impug" class="text-center">0</td>
                    <td id="per-impug" class="text-center">0</td>
                    <!--<td id="per-impug-abs">0</td>-->
                </tr>
                <tr>
                    <th scope="row">Total</th>
                    <td id="total" class="text-center">0</td>
                    <td id="per-total" class="text-center">0</td>
                    <!--<td id="per-total-abs">0</td>-->
                </tr>
                </tbody>
            </table>
        </div>
    </div>
