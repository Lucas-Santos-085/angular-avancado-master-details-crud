# 2.13

loadChildren: para carregar a rota de um módulo específico
{
path: "categories",
loadChildren: "./pages/categories/categories.module#CategoriesModule",
},

- path: src\app\app-routing.module.ts

# 2.14

routerLinkActive="active"

- Mostra qual opção do menu está ativa

      <li class="nav-item" routerLinkActive="active">
        <a class="nav-link" routerLink="/categories">Categorias</a>
      </li>

- path: src\app\app.component.html
