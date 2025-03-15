# Vragen? Neem contact op

<form action="https://dropbox.rohan-10.workers.dev" method="POST">
  <label for="name">Naam:</label><br>
  <input type="text" id="name" name="name" required><br>
  <label for="email">Email:</label><br>
  <input type="email" id="email" name="email" required><br>
  <label for="message">Bericht:</label><br>
  <textarea id="message" name="message" required></textarea><br>
  <input type="submit" value="Submit">
</form>

<style>
input[type="submit"] {
  align-items: center;
  background-image: linear-gradient(144deg,#AF40FF, #5B42F3 50%,#00DDEB);
  border: 0;
  border-radius: 8px;
  box-shadow: rgba(151, 65, 252, 0.2) 0 15px 30px -5px;
  box-sizing: border-box;
  font-size: 1em;
  color: #FFFFFF;
  display: flex;
  justify-content: center;
  line-height: 1em;
  max-width: 100%;
  min-width: 140px;
  padding: .7em 2em;
  text-decoration: none;
  user-select: none;
  -webkit-user-select: none;
  touch-action: manipulation;
  white-space: nowrap;
  cursor: pointer;
}

input[type="submit"]:active,
input[type="submit"]:hover {
  outline: 0;
}

@media (min-width: 768px) {
  input[type="submit"] {
    min-width: 196px;
  }
}
</style>