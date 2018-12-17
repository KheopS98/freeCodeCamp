# freeCodeCamp
Front-End Path FreeCodeCamp

<h3>Homeworks from Web_Boot_Camp</h3>
<hr>
<br>
<ul>
  <li>1.HTML Basics(Containt Lists)</li>
  <li>2.HTML Tables</li>
  <li>3.HTML Forms</li>
</ul>

<h4>1.HTML Basics</h4>
<h1>Things I've Learned</h1>
  <h2>Internet Basics</h2>
  <ol>
    <li>HTTP Request</li>
    <li>IP Adress</li>
    <li>Servers</li>
  </ol>

  <h2>HTML</h2>
  <ul>
    <li>Stands for <strong title="HTML">HyperText MarkUp Language</strong></li>
    <li>Lots of tags
      <ul>
        <li>Boilerplate
          <ol>
            <li>Doctype</li>
            <li>HTML</li>
            <li>Head
              <ol>
                <li>Title</li>
              </ol>
            </li>
            <li>Body</li>
          </ol>
        </li>
        <li>Headings</li>
        <li>Paragraphs</li>
        <li><em title="Empatized Text">em</em></li>
        <li><strong title="Strong Importance Text">strong</strong></li>
      </ul>
    </li>
  </ul>
  <hr>
  <br>
  
<h4>2.HTML Tables</h4>
 <h1>First Gen Pokemon Chart</h1>
    <table border="1">
      <thead>
        <tr>
          <th>Image</th>
          <th>Name</th>
          <th>Type</th>
          <th>Evolves Into</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td><img src="http://img4.wikia.nocookie.net/__cb20140328190757/pokemon/images/thumb/2/21/001Bulbasaur.png/200px-001Bulbasaur.png"></td>
          <td>Bulbasaur</td>
          <td>Grass/Poison</td>
          <td><a href="http://pokemon.wikia.com/wiki/Ivysaur ">Ivysaur</a></td>
        </tr>
        <tr>
          <td><img src="	http://img4.wikia.nocookie.net/__cb20140724195345/pokemon/images/thumb/7/73/004Charmander.png/200px-004Charmander.png" alt=""></td>
          <td>Charmander</td>
          <td>Fire</td>
          <td><a href="http://pokemon.wikia.com/wiki/Charmeleon ">Charmeleon</a></td>
        </tr>
        <tr>
          <td><img src="http://img1.wikia.nocookie.net/__cb20140328191525/pokemon/images/thumb/3/39/007Squirtle.png/200px-007Squirtle.png" alt=""></td>
          <td>Squirtle</td>
          <td>Water</td>
          <td><a href="http://pokemon.wikia.com/wiki/Wartortle">Wartortle</a></td>
        </tr>
      </tbody>
    </table>
<hr><br>

<h4>HTML Forms</h4>
<h2>Play with inputs</h2>
    <form action="process.php" method="post">
      <label for="firstname">First Name </label>
      <input id="firstname" type="text" placeholder="First Name" required >
      <br>
      <label for="lastname">Last Name</label>
      <input id="lastname"type="text" placeholder="Last Name" required>
      <br>
      <label for="email">Email</label>
      <input id="email" type="email" placeholder="username@example.com" required>
      <br>
      <label for="password">Password:</label>
      <input id="password" type="password" required>
      <br>
      <label for="confpassword">Confirm Password:</label>
      <input id="confpassword" type="password" required>
      <br>
      <label for="birth">BirthDay</label><
      <input id="birth" type="date" required>
      <br>
      <label for="age">Age</label>
      <input id="age"type="number" value="20" required>
      <br>
      <label for="color">Chose a color:</label>
      <input id="color" type="color" name="" value="" required>
      <br>
      <label for="cfile" >Chose your file </label>
      <input id="cfile" type="file" name="" value="" required>
      <br>
      <label for="gender">Gender</label>
      <select class="gender" name="gender">
        <option value="male">Male</option>
        <option value="female">Female</option>
        <option value="other">Other</option>
      </select>
      <br>
      <input type="checkbox"> <span>By clicking thatyou  are agree with our </span> <a href="Terms.html">Terms and conditions</a>
      <br>
      <input type="submit" name="" value="Submit">
    </form>
</div>

<!--Connect <label> and <input> with for and id atribute
  <label for="username">Username: </label>
  <input id="username" type="text" name="" value="" -->

  <label for="password">Password: </label>
  <input id="password" type="password" name="" value="">
<!--Validations for forms
  is done with  required atribute in input tags
  <input type="text" name="" value="" required>-->
  <hr><br>
  <!--Modul1 Finished -->
  <h3>FreeCodeCamp Mod1</h3>
  <h2>CatPhotoApp</h2>
<main>
  <p>Click here to view more <a href="#">cat photos</a>.</p>

  <a href="#"><img src="https://bit.ly/fcc-relaxing-cat" alt="A cute orange cat lying on its back."></a>

  <p>Things cats love:</p>
  <ul>
    <li>cat nip</li>
    <li>laser pointers</li>
    <li>lasagna</li>
  </ul>
  <p>Top 3 things cats hate:</p>
  <ol>
    <li>flea treatment</li>
    <li>thunder</li>
    <li>other cats</li>
  </ol>

  <form action="/submit-cat-photo">
    <label>
      <input type="radio" name="indoor-outdoor" checked> Indoor
    </label>
    <label>
      <input type="radio" name="indoor-outdoor"> Outdoor
    </label><br>
    <label>
      <input type="checkbox" name="personality" checked> Loving
    </label>
    <label>
      <input type="checkbox" name="personality">
    Lazy</label>
    <label>
      <input type="checkbox" name="personality"> Energetic
    </label><br>
    <input type="text" placeholder="cat photo URL" required>
    <button type="submit">Submit</button>
  </form>
</main>
