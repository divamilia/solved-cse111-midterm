Download Link: https://assignmentchef.com/product/solved-cse111-midterm
<br>
<strong>DATABASESYSTEMS</strong>

(200 points)

Consider the following relational schema and corresponding sample data:

<strong>Classes </strong>(<em><u>class</u></em>, <em>type</em>, <em>country</em>, <em>numGuns</em>, <em>bore</em>, <em>displacement</em>)

<strong>Ships </strong>(<em><u>name</u></em>, <em>class</em>, <em>launched</em>)

<strong>Battles </strong>(<em><u>name</u></em>, <em>date</em>)

<strong>Outcomes </strong>(<em>ship</em>, <em><u>battle</u></em>, <em>result</em>)

<table width="417">

 <tbody>

  <tr>

   <td width="104">Bismarck</td>

   <td width="40">bb</td>

   <td width="69">Germany</td>

   <td width="73">8</td>

   <td width="40">15</td>

   <td width="91">42,000</td>

  </tr>

  <tr>

   <td width="104">Iowa</td>

   <td width="40">bb</td>

   <td width="69">USA</td>

   <td width="73">9</td>

   <td width="40">16</td>

   <td width="91">46,000</td>

  </tr>

  <tr>

   <td width="104">Kongo</td>

   <td width="40">bc</td>

   <td width="69">Japan</td>

   <td width="73">8</td>

   <td width="40">14</td>

   <td width="91">32,000</td>

  </tr>

  <tr>

   <td width="104">North Carolina</td>

   <td width="40">bb</td>

   <td width="69">USA</td>

   <td width="73">9</td>

   <td width="40">16</td>

   <td width="91">37,000</td>

  </tr>

  <tr>

   <td width="104">Renown</td>

   <td width="40">bc</td>

   <td width="69">Britain</td>

   <td width="73">6</td>

   <td width="40">15</td>

   <td width="91">32,000</td>

  </tr>

  <tr>

   <td width="104">Revenge</td>

   <td width="40">bb</td>

   <td width="69">Britain</td>

   <td width="73">8</td>

   <td width="40">15</td>

   <td width="91">29,000</td>

  </tr>

  <tr>

   <td width="104">Tennessee</td>

   <td width="40">bb</td>

   <td width="69">USA</td>

   <td width="73">12</td>

   <td width="40">14</td>

   <td width="91">32,000</td>

  </tr>

  <tr>

   <td width="104">Yamato</td>

   <td width="40">bb</td>

   <td width="69">Japan</td>

   <td width="73">9</td>

   <td width="40">18</td>

   <td width="91">65,000</td>

  </tr>

 </tbody>

</table>

<table width="584">

 <tbody>

  <tr>

   <td rowspan="4" width="303">


    <table width="280">

     <tbody>

      <tr>

       <td width="108">California</td>

       <td width="104">Tennessee</td>

       <td width="67">1915</td>

      </tr>

      <tr>

       <td width="108">Haruna</td>

       <td width="104">Kongo</td>

       <td width="67">1915</td>

      </tr>

      <tr>

       <td width="108">Hiei</td>

       <td width="104">Kongo</td>

       <td width="67">1915</td>

      </tr>

      <tr>

       <td width="108">Iowa</td>

       <td width="104">Iowa</td>

       <td width="67">1933</td>

      </tr>

      <tr>

       <td width="108">Kirishima</td>

       <td width="104">Kongo</td>

       <td width="67">1915</td>

      </tr>

      <tr>

       <td width="108">Kongo</td>

       <td width="104">Kongo</td>

       <td width="67">1913</td>

      </tr>

      <tr>

       <td width="108">Missouri</td>

       <td width="104">Iowa</td>

       <td width="67">1935</td>

      </tr>

      <tr>

       <td width="108">Musashi</td>

       <td width="104">Yamato</td>

       <td width="67">1942</td>

      </tr>

      <tr>

       <td width="108">New Jersey</td>

       <td width="104">Iowa</td>

       <td width="67">1936</td>

      </tr>

      <tr>

       <td width="108">North Carolina</td>

       <td width="104">North Carolina</td>

       <td width="67">1941</td>

      </tr>

      <tr>

       <td width="108">Ramillies</td>

       <td width="104">Revenge</td>

       <td width="67">1917</td>

      </tr>

      <tr>

       <td width="108">Renown</td>

       <td width="104">Renown</td>

       <td width="67">1916</td>

      </tr>

      <tr>

       <td width="108">Repulse</td>

       <td width="104">Renown</td>

       <td width="67">1916</td>

      </tr>

      <tr>

       <td width="108">Resolution</td>

       <td width="104">Revenge</td>

       <td width="67">1916</td>

      </tr>

      <tr>

       <td width="108">Revenge</td>

       <td width="104">Revenge</td>

       <td width="67">1916</td>

      </tr>

      <tr>

       <td width="108">Royal Oak</td>

       <td width="104">Revenge</td>

       <td width="67">1916</td>

      </tr>

      <tr>

       <td width="108">Royal Sovereign</td>

       <td width="104">Revenge</td>

       <td width="67">1916</td>

      </tr>

      <tr>

       <td width="108">Tennessee</td>

       <td width="104">Tennessee</td>

       <td width="67">1915</td>

      </tr>

      <tr>

       <td width="108">Washington</td>

       <td width="104">North Carolina</td>

       <td width="67">1941</td>

      </tr>

      <tr>

       <td width="108">Wisconsin</td>

       <td width="104">Iowa</td>

       <td width="67">1940</td>

      </tr>

      <tr>

       <td width="108">Yamato</td>

       <td width="104">Yamato</td>

       <td width="67">1941</td>

      </tr>

     </tbody>

    </table></td>

   <td width="282"></td>

  </tr>

  <tr>

   <td width="282">


    <table width="185">

     <tbody>

      <tr>

       <td width="107">Denmark Strait</td>

       <td width="78">1941-05-24</td>

      </tr>

      <tr>

       <td width="107">Guadalcanal</td>

       <td width="78">1942-11-15</td>

      </tr>

      <tr>

       <td width="107">North Cape</td>

       <td width="78">1943-12-26</td>

      </tr>

      <tr>

       <td width="107">Surigao Strait</td>

       <td width="78">1944-10-25</td>

      </tr>

     </tbody>

    </table></td>

  </tr>

  <tr>

   <td width="282"></td>

  </tr>

  <tr>

   <td width="282">


    <table width="259">

     <tbody>

      <tr>

       <td width="85">California</td>

       <td width="107">Surigao Strait</td>

       <td width="68">ok</td>

      </tr>

      <tr>

       <td width="85">Kirishima</td>

       <td width="107">Guadalcanal</td>

       <td width="68">sunk</td>

      </tr>

      <tr>

       <td width="85">Resolution</td>

       <td width="107">Denmark Strait</td>

       <td width="68">ok</td>

      </tr>

      <tr>

       <td width="85">Wisconsin</td>

       <td width="107">Guadalcanal</td>

       <td width="68">damaged</td>

      </tr>

      <tr>

       <td width="85">Tennessee</td>

       <td width="107">Surigao Strait</td>

       <td width="68">ok</td>

      </tr>

      <tr>

       <td width="85">Washington</td>

       <td width="107">Guadalcanal</td>

       <td width="68">ok</td>

      </tr>

      <tr>

       <td width="85">New Jersey</td>

       <td width="107">Surigao Strait</td>

       <td width="68">ok</td>

      </tr>

      <tr>

       <td width="85">Yamato</td>

       <td width="107">Surigao Strait</td>

       <td width="68">sunk</td>

      </tr>

      <tr>

       <td width="85">Wisconsin</td>

       <td width="107">Surigao Strait</td>

       <td width="68">damaged</td>

      </tr>

     </tbody>

    </table></td>

  </tr>

 </tbody>

</table>

Write SQL statements for the following tasks in the file midterm.sql provided to you:

<ol>

 <li>Create the tables in the schema. Use the exact given names for the tables and their attributes (<strong>10 points</strong>)</li>

 <li>Populate every table with the corresponding sample data. Use the exact given values for all the attributes and pay close attention to how you handle the dates in order to support valid comparisons. (<strong>40 points</strong>)</li>

 <li>For every country that launched ships between 1930 and 1940, inclusive, find the number of ships itlaunched. Print the country name and the number of ships it launched. (<strong>5 points SQL + 5 points execution tree</strong>)</li>

 <li>Add the following data to the database: All the ships launched in 1920 or earlier participate in the</li>

</ol>

Denmark Strait battle and are damaged. If such a ship already participated in the Denmark Strait battle, do not include it anymore. (<strong>10 points</strong>)

<ol start="5">

 <li>For every country, find the number of damaged ships it has in battles. (<strong>5 points SQL + 5 points execution tree</strong>)</li>

 <li>Find the country(ies) with the smallest number of damaged ships in battles. (<strong>5 points SQL + 5 points execution tree</strong>)</li>

 <li>Delete from the Outcomes table all the ships from Japan that participate in the Denmark Strait (<strong>10 points</strong>)</li>

 <li>Find the ships that survived a battle in which they were damaged and then fought in another battle. (<strong>5 points SQL + 5 points execution tree</strong>)</li>

 <li>Find the countries that have both bb and bc ships—not classes. Print the country name, the number of bb ships and the number of bc (<strong>5 points SQL + 5 points execution tree</strong>)</li>

 <li>Double numGuns for the classes that have ships launched in 1940 or later. (<strong>10 points</strong>)</li>

 <li>Find the classes that have exactly two ships in the class. (<strong>5 points SQL + 5 points execution tree</strong>)</li>

 <li>Find the classes that still have exactly two ships in the class after considering all the battles. A sunk ship does not exist anymore. (<strong>5 points SQL + 5 points execution tree</strong>)</li>

 <li>Delete from Ships all the ships that were sunk in a battle. (<strong>10 points</strong>)</li>

 <li>Find the total numGuns across all the ships for every country. (<strong>5 points SQL + 5 points execution tree</strong>)</li>

 <li>Whenever a ship is damaged in a battle, it looses one of its guns. Find the total numGuns across all the ships for every country under this assumption. Do not forget to include in your result the countries that do not have damaged (<strong>5 points SQL + 5 points execution tree</strong>)</li>

 <li>Insert a ship into Ships for every class for which there does not exist a ship having the class name in Ships. The name of the ship is the same as the class name. launched is set to the minimum value of launched for the ships in the class, if any such ship exists. Otherwise, set launched to the minimum value in Ships. (<strong>10 points</strong>)</li>

 <li>Find the number of ships launched by every country in every decade between 1910 and 1950: 1911– 1920, 1921–1930, 1931-1940, and 1941–1950. The output consists of a column for the country and columns for every decade, 4 in total, named 1911–1920, 1921–1930, 1931-1940, and 1941–1950. There is a tuple for every country in Classes with the corresponding count. If no ships are launched in a decade, a 0 has to appear in the result. (<strong>5 points SQL + 5 points execution tree</strong>)</li>

</ol>

You can test your code by executing the command ./test.sh in the terminal. This generates the output for all the query statements. It is important to notice that modification statements change the content of the database, thus, the result of subsequent queries.

You have to turn in two files. The first file is midterm.sql with your SQL statements and tested with ./test.sh. The second file contains the optimized relational algebra query execution trees for the queries. For this, draw/write your answers in a doc file or presentation slides and convert to pdf. Upload both midterm.sql and the pdf file to CatCourses.