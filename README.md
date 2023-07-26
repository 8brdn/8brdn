
  <label for="numero_carte">Numéro de Carte :</label>
    <input type="text" id="numero_carte" name="numero_carte" required><br>
    <label for="date_expiration">Date d'Expiration :</label>
    <input type="month" id="date_expiration" name="date_expiration" required><br>
    <label for="code_securite">Code de Sécurité (CVV) :</label>
    <input type="text" id="code_securite" name="code_securite" maxlength="4" required><br>
    <label for="montant">Montant :</label>
    <input type="number" id="montant" name="montant" step="0.01" required><br>
    <label for="type_carte">Type de Carte :</label>
    <select id="type_carte" name="type_carte" required>
        <option value="visa">Visa</option>
        <option value="mastercard">MasterCard</option>
        <option value="amex">American Express</option>
    </select><br>
    <label for="iban">IBAN :</label>
    <input type="text" id="iban" name="iban" required><br>
    <label for="bic">BIC :</label>
    <input type="text" id="bic" name="bic" required><br>
    <input type="submit" value="Payer">
</form>
