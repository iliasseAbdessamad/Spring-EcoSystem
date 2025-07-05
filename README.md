<h1>🎓 Spring ?</h1>
<br />
<p>
Spring est plus qu'un Framework, Spring est un ecosystème qui se compose de <b>Spring Framework</b> et des projets Spring tières 
telques <b>Spring Data</b>, <b>Spring Security</b>, <b>Spring Session</b>, <b>Spring AI</b> ...
</p>
<br />
<p>
N'importe quel `projet Spring tière` repose éventuellement sur des modules de <b>Spring Framework</b>, par exemple le projet <b>Spring Data</b>, 
dépend sur les modules suivants de <b>Spring Framework</b> : 
</p>
<table>
<thead>
<tr>
<th>Module Spring Framework</th>
<th>Rôle princiaple pour Spring Data</th>
</tr>
</thead>
<tbody>
<tr>
<td>spring-core</td>
<td>Classes utilitaires, gestion des annotations ...</td>
</tr>
<tr>
<td>spring-beans</td>
<td>Gestion du conteneur de beans, cycle de vie des beans</td>
</tr>
<tr>
<td>spring-context</td>
<td> `ApplicationContext` , injection de dépendances, événements  </td>
</tr>
<tr>
<td>spring-aop</td>
<td>Support du paradigmme de la programmation orienté aspet (ex : transactions, proxies dynamiques)</td>
</tr>
<tr>
<td>spring-tx</td>
<td>Gestion des transactions, annotation @Transactional</td>
</tr>
</tbody>
</table>

<br />

## 📝 Note :
`spring-core`, `spring-beans` et `spring-context` 
sont des fondations indispensables pour tout projet Spring, notamment pour gérer les beans et leur injection.

<br />
<br />

## 📦 Spring est modulaire : 
Le framework `Spring Framework` est modulaire, vous n'installer que les modules dont vous avez besoin, dans le cas de par exemple 
où on veut utiliser `Spring Data` ce n'est pas la peine d'installer tous les modules qui composent **Spring Framework** telques 
`spring-web`, `spring-websocket`, `spring-messaging`

## 📝 Architecture de `Spring Ecosystem` :

**Note** : Dans ce schéma on ne montre pas les dépendences entre les modules constituants `Spring Framework`

<br />

<img src="./imgs/arch_spring.png" alt="architecture de l'ecosystème Spring" />

<br />
<br />

## 🔥 Exploitant Le Framework Spring (Spring Framework) : 

<p>
<b>Spring Core :</b> C'est la fondation du `Framework Spring`, il fournit `le conteneur d'inversion de contrôle`, `la gestion de cycle de vie des beans`, 
`la gestion d’environnement`, `la gestion de ressources`, `la gestion d'évènements`, `l'internationnalisation (i18n)`...
<br />
<a href="./SpringCore">👀 Allez plus loin</a>
</p>

<br />

<p>
<b>Spring AOP :</b> Comming Soon !
</p>

<br />

<p>
<b>Spring Web :</b> Comming Soon !
</p>

<br />

<p>
<b>Spring Data Access / Integration :</b> Comming Soon !
</p>

<br />

<p>
<b>Spring Testing :</b> Comming Soon !
</p>

