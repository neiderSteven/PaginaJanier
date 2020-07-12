#PUBLICAR LA PAGINA EN GITHUB

ng add angular-cli-ghpages
ng deploy pagina-principal-janier
ng deploy --repo=https://github.com/<neidersteven>/<paginaPrincipalJanierneidersteven>.git --name="Your Git Username" --email=rodriguezneiderstiven@gmail.com
ng build --prod --base-href https://neidersteven.github.io/PaginaJanier/
npx ngh --dir=dist/PaginaPrincipal-Janier 
