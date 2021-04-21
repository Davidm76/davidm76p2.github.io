<!DOCTYPE html>
<html>
          <head>
                    <meta charset="utf-8" />
                    <meta name="viewport" content="width=device-width, initial-scale=1.0">
                    <link rel="stylesheet" href="style.css" />
                    <script src="https://kit.fontawesome.com/d745661341.js" crossorigin="anonymous"></script>
                    <title>Reservia</title>
          </head>

          <body>
                    <main>
                              <header>
                    
               
                                        <div class="bloc1">
                                                  <img src="image/Reservia.svg" alt="logo reservia"/>
                                                  <nav class="menu1">          
                                                            <a class="active" href="#hébergements">Hébergements</a>
                                                            <a href="#activités">Activités</a>
                                                            <a href="s'inscrire">S'inscrire</a>                                                                      
                                                  </nav>
                                        </div>
                                        <div class="bloc1_mobile">
                                                  <nav>
                                                            <a href="index.html"><img src="image/Reservia.svg" alt="logo reservia"/></a>
                                                            <a href="s'inscrire">S'inscrire</a>
                                                  </nav>
                                                  <nav>          
                                                            <a class="active" href="#hébergements">Hébergements</a>
                                                            <a href="#activités">Activités</a>                                                                      
                                                  </nav>
                                        </div>
                                        <h1>Trouvez votre hébergement pour des vacances de rêve</h1>
                                        <p>En plein centre ville ou en pleine nature</p>
                                             
                                        <form method="post" action="traitement.php">
                                                  <div>     
                                                            <label for="ville_pays"><i class="fas fa-map-marker-alt" alt="icone"></i></label>
                                                  </div>
                                                  <div>
                                                            <input class="form" type="text" name="ville_pays" id="ville_pays" placeholder="Marseille, France"/>
                                                  </div>
                                                  <div>
                                                            <input class="rechercher" type="submit" value="Rechercher"/>
                                                  </div>
                                                  <div>
                                                            <button><i class="fas fa-search"></i></button>
                                                  </div> 
                                        </form>

                                        <div class="bloc2">
                                                  <p class="filtre">Filtres</p>
                                                  <section>
                                                            <div class="économique">
                                                                      <span class="fas fa-money-bill-wave"></span><p>&Eacute;conomique</p>                                                                                         
                                                            </div>
                                                            <div class="familial">
                                                                      <span class="fas fa-child"></span><p>Familial</p>                                                                                      
                                                            </div>
                                                            <div class="romantique">
                                                                      <span class="fas fa-heart"></span><p>Romantique</p>                                                                                        
                                                            </div>
                                                            <div class="animaux">
                                                                      <span class="fas fa-dog"></span><p>Animaux autorisés</p>
                                                            </div>                                                                                     
                                                  </section>
                                        </div>
                                                            
                              </header>

                              
                              <p><span class="fas fa-info"></span>Plus de 500 logements sont disponibles dans cette ville<br /></p>

                              <section class="bloc3">
                                        <div class="héber">                                                           
                                                            
                                                  <h2>Hébergements à Marseille</h2>
                                                  <div class="héber_1">
                                                            <a href="#" class="p1">
                                                                      <div class="vignette">
                                                                                <img src="image/marcus-loke-WQJvWU_HZFo-unsplash.jpg" alt="auberge la Cannebière">
                                                                                <div>
                                                                                          <p><b>Auberge La Cannebière</b><br /></p>
                                                                                          <p>Nuit à partir de 25€</p>
                                                                                          <i class="fas fa-star"></i>
                                                                                          <i class="fas fa-star"></i>
                                                                                          <i class="fas fa-star"></i>
                                                                                          <i class="fas fa-star"></i>
                                                                                          <i class="fas fa-star"></i>
                                                                                </div>
                                                                      </div>
                                                            </a>
                                                            <a href="#" class="p2">
                                                                      <div class="vignette">
                                                                                <img src="image/fred-kleber-gTbaxaVLvsg-unsplash.jpg" alt="hôtel du port">
                                                                                <div>
                                                                                          <p><b>Hôtel du port</b><br /></p>
                                                                                          <p>Nuit à partir de 52€</p>
                                                                                          <i class="fas fa-star"></i>
                                                                                          <i class="fas fa-star"></i>
                                                                                          <i class="fas fa-star"></i>
                                                                                          <i class="fas fa-star"></i>
                                                                                          <i class="fas fa-star"></i>
                                                                                </div>
                                                                      </div>               
                                                            </a>         
                                                            <a href="#" class="p3">
                                                                      <div class="vignette">
                                                                                <img src="image/reisetopia-B8WIgxA_PFU-unsplash.jpg" alt="Hôtel Les mouettes">                                                                                        
                                                                                <div>
                                                                                          <p><b>Hôtel Les mouettes</b><br /></p>
                                                                                          <p>Nuit à partir de 76€</p>
                                                                                          <i class="fas fa-star"></i>
                                                                                          <i class="fas fa-star"></i>
                                                                                          <i class="fas fa-star"></i>
                                                                                          <i class="fas fa-star"></i>
                                                                                          <i class="fas fa-star"></i> 
                                                                                 </div>
                                                                      </div>
                                                            </a>
                                                  </div>
                                                  <div class="héber_2">
                                                            <a href="#" class="p4">
                                                                      <div class="vignette">
                                                                                <img class="image4" src="image/annie-spratt-Eg1qcIitAuA-unsplash.jpg" alt="Hôtel de la mer">
                                                                                <div>
                                                                                          <p><b>Hôtel de la mer</b><br /></p>
                                                                                          <p>Nuit à partir de 46€</p>
                                                                                          <i class="fas fa-star"></i>
                                                                                          <i class="fas fa-star"></i>
                                                                                          <i class="fas fa-star"></i>
                                                                                          <i class="fas fa-star"></i>
                                                                                          <i class="fas fa-star"></i>       
                                                                                </div> 
                                                                      </div>
                                                            </a>
                                                            <a href="#" class="p5">
                                                                      <div class="vignette">
                                                                                <img src="image/nicate-lee-kT-ZyaiwBe0-unsplash.jpg" alt="Auberge Le Panier">
                                                                                <div>
                                                                                          <p><b>Auberge Le Panier</b><br /></p>
                                                                                          <p>Nuit à partir de 23€</p>
                                                                                          <i class="fas fa-star"></i>
                                                                                          <i class="fas fa-star"></i>
                                                                                          <i class="fas fa-star"></i>
                                                                                          <i class="fas fa-star"></i>
                                                                                          <i class="fas fa-star"></i>
                                                                                </div>
                                                                      </div>               
                                                            </a>
                                                                           
                                                            <a href="#" class="p6">
                                                                      <div class="vignette">
                                                                                <img class="image6" src="image/febrian-zakaria-M6S1WvfW68A-unsplash.jpg" alt="Hôtel chez Amina">
                                                                                <div>
                                                                                          <p><b>Hôtel chez Amina</b><br /></p>
                                                                                          <p>Nuit à partir de 96€</p>
                                                                                          <i class="fas fa-star"></i>
                                                                                          <i class="fas fa-star"></i>
                                                                                          <i class="fas fa-star"></i>
                                                                                          <i class="fas fa-star"></i>
                                                                                          <i class="fas fa-star"></i>
                                                                                </div>
                                                                      </div>
                                                            </a>
                                                  </div>
                                                  <p><b>Afficher plus</b></p>
                                        </div>

                                                                           
                                                            
                                                              
                                        <div class="pop">
                                                  <div class="titre_pop">
                                                            <h2>Les plus populaires</h2>
                                                            <i class="fas fa-chart-line"></i>
                                                  </div>
                                                  <a href="#" class="p7">
                                                            <div class="vignette_populaire">
                                                                      <img src="image/emile-guillemot-Bj_rcSC5XfE-unsplash.jpg" alt="Hôtel Le soleil du matin">
                                                                      <div class="description">
                                                                                <p><b>Hôtel Le soleil du matin</b><br /></p>
                                                                                <p>Nuit à partir de 128€</p>
                                                                                <div class="étoile">
                                                                                          <i class="fas fa-star"></i>
                                                                                          <i class="fas fa-star"></i>
                                                                                          <i class="fas fa-star"></i>
                                                                                          <i class="fas fa-star"></i>
                                                                                          <i class="fas fa-star"></i>
                                                                                </div>
                                                                      </div>
                                                            </div>
                                                  </a>
                                                  <a href="#" class="p8">
                                                            <div class="vignette_populaire">
                                                                      <img class="photo_8" src="image/aw-creative-VGs8z60yT2c-unsplash.jpg" alt="Au coeur de l'eau Chambres d'hôtes">
                                                                      <div class="description">                         
                                                                                <p><b>Au coeur de l'eau Chambres d'hôtes</b><br /></p>
                                                                                <p>Nuit à partir de 71€</p>
                                                                                <div class="étoile">
                                                                                          <i class="fas fa-star"></i>
                                                                                          <i class="fas fa-star"></i>
                                                                                          <i class="fas fa-star"></i>
                                                                                          <i class="fas fa-star"></i>
                                                                                          <i class="fas fa-star"></i>
                                                                                </div>
                                                                      </div>
                                                            </div>
                                                  </a>
                                                  <a href="#" class="p9">
                                                            <div class="vignette_populaire">
                                                                      <img src="image/febrian-zakaria-sjvU0THccQA-unsplash.jpg" alt="Hôtel Tout bleu et blanc">
                                                                      <div class="description">
                                                                                <p><b>Hôtel Tout bleu et Blanc</b><br /></p>
                                                                                <p> à partir de 68€</p>
                                                                                <div class="étoile">
                                                                                          <i class="fas fa-star"></i>
                                                                                          <i class="fas fa-star"></i>
                                                                                          <i class="fas fa-star"></i>
                                                                                          <i class="fas fa-star"></i>
                                                                                          <i class="fas fa-star"></i>
                                                                                </div>
                                                                      </div>
                                                            </div>
                                                  </a>
                                        </div>
                              </section> 
                              
                              <section>

                                        <div class="bloc4">
                                                  <div>
                                                  <h2 id="activités">Activités à Marseille</h2>
                                                                           
                                                  
                                                            <div class="structure_photo">    
                                                                      <div class="photo_1">  
                                                                                          <img class="grande" src="image/reno-laithienne-QUgJhdY5Fyk-unsplash.jpg" alt="Vieux Port">                                                                                                                                           
                                                                                          <p class="texte">Vieux Port</p>
                                                                      </div>                 
                                                                      <div class="photo_2_3">
                                                                                <div>
                                                                                          <img class="petite" src="image/paul-hermann-QFTrLdQIRhI-unsplash.jpg" alt="Fort de Pomègues">
                                                                                          <p class="texte">Fort de Pomègues</p>  
                                                                                </div>
                                                                                <div>
                                                                                          <img class="petite" src="image/kevin-hikari-rV_Qd1l-VXg-unsplash.jpg" alt="Ile du Frioul">
                                                                                          <p class="texte">&icircles du Frioul</p>
                                                                                </div>                                                                                                                                                                                                                                     
                                                                      </div>
                                                                      <div class="photo_4">                                                    
                                                                                <img class="grande" src="image/kilyan-sockalingum-NR8-cBCN3aI-unsplash.jpg" alt="Parc National des Calanques">
                                                                                <p class="texte">Parc National des Calanques</p>                                                                                          
                                                                      </div>
                                                                      <div class="photo_5_6">                                                    
                                                                                <div>
                                                                                          <img class="petite" src="image/florian-wehde-xW9e8gdotxI-unsplash.jpg" alt="Notre-dame-de-la-Garde">
                                                                                          <p class="texte">Notre-dame-de-la-Garde</p>  
                                                                                </div>
                                                                                <div>
                                                                                          <img class="petite" src="image/lena-paulin-wH2-EJoDcV0-unsplash.jpg" alt="Parc Longchamp">
                                                                                          <p class="texte">Parc Longchamp</p>
                                                                                </div>
                                                                      </div>
                                                            </div>                                                          
                                                  </div>             
                              </section>
                    </main>

                              <footer>
                                        <section class="bas_page">
                                                  <aside>
                                                            <p class="titre"> A propos</p>
                                                            <p> fonctionnement du site</p>
                                                            <p> Conditions générales de vente</p>
                                                            <p> Données et Confidentialité</p>
                                                  </aside>
                                                  <aside>
                                                            <p class="titre"> Nos hébergements</p>
                                                            <p> Charte qualité</p>
                                                            <p> Soumettre votre hôtel</p>
                                                  </aside>
                                                  <aside>
                                                            <p class="titre"> Assistance</p>
                                                            <p> Centre d'aide</p>
                                                            <p> Nous contacter</p>
                                                  </aside>
                                        </section>
                              </footer>

               </body>

</html>
