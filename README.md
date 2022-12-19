<div align="left">  
  <div>
      <b><a target="_blank" href="https://github.com/fastify">Fastify</a></b>
      <p>
      <li>Supporting different content-type responses <a href="https://github.com/fastify/fastify/pull/4264">#175</a></li>
      <li>rendering the syntax of different content types responses @ Fastify/Swagger <a href="https://github.com/fastify/fastify-swagger/pull/665">#665</a></li>
      <li>Introducing the default relation plugin option @ Fastify/Auth <a href="https://github.com/fastify/fastify-auth/pull/175">#175</a></li>
      <li>Updating typescript example according to the validation changes <a href="https://github.com/fastify/fastify/pull/4261">#4261</a></li>
      </p>
      <b><a target="_blank" href="https://github.com/facebook/jest/">Facebook/Jest</a></b>
    <p>
      <li>Enhancing the toHaveProperty matcher to support array selection <a href="https://github.com/facebook/jest/pull/12092">#12092</a></li>
    </p>
          <b><a target="_blank" href="https://github.com/socketio">Socket.IO</a></b>
    <p>
      <li>Adding an option to avoid the added trailing slash to the path <a href="https://github.com/socketio/engine.io-client/pull/694">#694</a></li>
    </p>
    <b><a target="_blank" href="https://github.com/phpmyadmin/sql-parser/">PhpMyAdmin/SQL-Parser</a></b>
    <p>
      <li>Fixing buffered query when has odd number of backslashes in the end <a href="https://github.com/phpmyadmin/sql-parser/pull/340">#340</a></li>
      <li>Fixing the issue of ignoring the body tokens when creating views with `union` <a href="https://github.com/phpmyadmin/sql-parser/pull/343">#343</a></li>
      <li>Fixing parser errors when adding columns with SET type <a href="https://github.com/phpmyadmin/sql-parser/pull/344">#344</a></li>
        <li>Adding the support of altering user options <a href="https://github.com/phpmyadmin/sql-parser/pull/345">#345</a></li>
       <li>Fixing the issue of not handling the procedures’ options <a href="https://github.com/phpmyadmin/sql-parser/pull/346">#346</a></li>
       <li>Fixing missing KEY options for MySQL and MariaDB <a href="https://github.com/phpmyadmin/sql-parser/pull/354">#354</a></li>
       <li>Fixing the validation exception when using enforced options <a href="https://github.com/phpmyadmin/sql-parser/pull/355">#355</a></li>
           <li>Adding over keyword to the contexts and modify the Expression allowed keywords <a href="https://github.com/phpmyadmin/sql-parser/pull/360">#360</a></li>
          <li>Completing, refactoring an improving the WITH statements parser <a href="https://github.com/phpmyadmin/sql-parser/pull/363">#363</a></li>
      <li>Fixing the additional body tokens issue when create view statements  <a href="https://github.com/phpmyadmin/sql-parser/pull/371">#371</a></li>
      <li>Supporting table structure with COMPRESSED columns <a href="https://github.com/phpmyadmin/sql-parser/pull/380">#380</a></li>
       <li>Supporting ALTER queries of PARTITIONS <a href="https://github.com/phpmyadmin/sql-parser/pull/381">#381</a></li>
       <li>Supporting the compression options in create table statements <a href="https://github.com/phpmyadmin/sql-parser/pull/382">#382</a></li>
      <li>Lexer - Solving ambiguity on function keywords <a href="https://github.com/phpmyadmin/sql-parser/pull/385">#385</a></li>
       <li>Differentiating between analyze and explain statements <a href="https://github.com/phpmyadmin/sql-parser/pull/386">#386</a></li>
       <li>Adding NOT to the select options <a href="https://github.com/phpmyadmin/sql-parser/pull/388">#388</a></li>
       <li>Implementing the EXPLAIN Parser <a href="https://github.com/phpmyadmin/sql-parser/pull/389">#389</a></li>
       <li>Allowing the NOT keyword as an expression <a href="https://github.com/phpmyadmin/sql-parser/pull/391">#391</a></li>
       <li>Updated contexts to contain multipoint and multipolygon data types <a href="https://github.com/phpmyadmin/sql-parser/pull/393">#393</a></li>
      <li>Testing the contextGenerator class <a href="https://github.com/phpmyadmin/sql-parser/pull/394">#394</a></li>
      <li>Performance improvement to use less the "nextToken()" function  <a href="https://github.com/phpmyadmin/sql-parser/pull/397">#397</a></li>
      <li>Improving the Expression component's allowed keywords <a href="https://github.com/phpmyadmin/sql-parser/pull/399">#399</a></li>
      <li>Fixing tests on php 8.3 - making getMergedOptions protected <a href="https://github.com/phpmyadmin/sql-parser/pull/400">#400</a></li>
    </p>
       <b><a target="_blank" href="https://github.com/sideway/joi/">Joi</a></b>
    <p>
       <li>Fixing an unhandled feature that fill the default values when used in an ordered array schema <a href="https://github.com/sideway/joi/pull/2548">#2548</a></li>
    </p>
     <b><a target="_blank" href="https://github.com/appwrite">Appwrite</a></b>
    <p>
       <li>Fixing the create team membership API to return added person information <a href="https://github.com/appwrite/appwrite/pull/3590">#3590</a></li>
    </p>
    <b><a target="_blank" href="https://github.com/nuxt-community/i18n-module/">Nuxt-community/i18n-module</a></b>
    <p>
       <li>Adding direction property and defaultDirection option <a href="https://github.com/nuxt-community/i18n-module/pull/1023">#1023</a></li>
      <li>Exposing localeProperties property to access the properties of current locale <a href="https://github.com/nuxt-community/i18n-module/pull/1016">#1016</a></li>
      <li>Fixing localeProperties became undefined when <i18n> component is used <a href="https://github.com/nuxt-community/i18n-module/pull/1043">#1043</a></li>
    </p>
        <b><a target="_blank" href="https://github.com/phpmyadmin/phpmyadmin/">PhpMyAdmin</a></b>
    <p>
      <li>Fixing a query generation bug which allows specifying a length for JSON fields <a href="https://github.com/phpmyadmin/phpmyadmin/pull/16643">#16643</a></li>
             <li>Fixing a bug that occurs when default current_timestamp is used with on update current_timestamp <a href="https://github.com/phpmyadmin/phpmyadmin/pull/16653">#16653</a></li>
                   <li>Ignore the length of the integer types and show a warning <a href="https://github.com/phpmyadmin/phpmyadmin/pull/16767">#16767</a></li>
      <li>Fixing the designer issue - supporting the RTL mode <a href="https://github.com/phpmyadmin/phpmyadmin/pull/16814">#16814</a></li>
       <li>Fixing the null issue with datetime in insert mode <a href="https://github.com/phpmyadmin/phpmyadmin/pull/17008">#17008</a></li>
       <li>Fixing the issue when assigning database to user with ‘_’ <a href="https://github.com/phpmyadmin/phpmyadmin/pull/17010">#17010</a></li>
      <li>Fixing the case-sensitive issue of innodb_file_format <a href="https://github.com/phpmyadmin/phpmyadmin/pull/17013">#17013</a></li>
             <li>Fixing all issues related to assigning privileges to databases with `_`  <a href="https://github.com/phpmyadmin/phpmyadmin/pull/17015">#17015</a></li>
       <li>Fixing the issue of hiding the structure options while exporting  <a href="https://github.com/phpmyadmin/phpmyadmin/pull/17043">#17043</a></li>
 <li>Escaping the databases when granting pribileges on tables <a href="https://github.com/phpmyadmin/phpmyadmin/pull/17044">#17044</a></li>
             <li>Fixing the issues regarding granting/showing privileges from privileges tab <a href="https://github.com/phpmyadmin/phpmyadmin/pull/17045">#17045</a></li>
      <li>Supporting the Page/Column Compression options for mariaDB <a href="https://github.com/phpmyadmin/phpmyadmin/pull/17657">#17657</a></li>
      <li>default to "Full texts" when running explain statements <a href="https://github.com/phpmyadmin/phpmyadmin/pull/17906">#17906</a></li>
    </p>
       <b><a target="_blank" href="https://github.com/outline/outline">Outline</a></b>
    <p>
        <li>Improving the urls to not break protocols and testing the urls utilities <a href="https://github.com/outline/outline/pull/3995">#3995</a></li>
    </p>
          <b><a target="_blank" href="https://github.com/graphql/graphiql/">Graphql/Graphiql</a></b>
    <p>
       <li>Fixing the search icon misalignment <a href="https://github.com/graphql/graphiql/pull/1776">#1776</a></li>
    </p>
     
  </div>
</div>
<hr/>
