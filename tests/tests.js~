var assert = chai.assert;

suite('Pruebas ', function() {
    test('1.Si la salida es una cadena', function() {
        original.value = "Hola, Adios, Mesa";
        calculate();
        assert.isString(finaltable.innerHTML);
    });
    
    test('2. Saltos de lineas', function() {
        original.value = "";
        calculate();
        assert.deepEqual(finaltable.innerHTML,'<p>\n</p><table class="center" id="result">\n</table>');
    });
    test('3. Si no se inserta nada salta un error', function() {
        original.value = "";
        calculate();
        assert.deepEqual(finaltable.innerHTML, '<p>\n</p><table class="center" id="result">\n</table>');
    });
});