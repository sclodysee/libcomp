# libcomp
Librairie de composants - Standalone et Custom  
Basée sur le projet KeenUI

Les composants 'standalone' nécessitent plusieurs choses :  

1. la librairie VueJS doit être intégrée dans le fichier html.
2. le composant doit être initialisé manuellement (new Vue({...})
3. une 'div' de destination doit être déclarée lors de l'initialisation


Les composants 'custom elements' se comportent comme de vraies balises html.  

Ils ne nécessitent aucune déclaration ou initialisation et peuvent s'initégrer  
n'importe où dans la page html.  

La contrainte (temporaire) est d'inclure un fichier de compatibilité pour les navigateurs  
qui ne supportent pas encore cette fonctionnalité.  

  
 La librairie **libcomp** permet de produire ces deux types de composants.  
 
