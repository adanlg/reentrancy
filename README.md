# Contratos y guía para realizar ataque de reentrada
1. Ve a https://remix.ethereum.org/ para un despliegue fácil y rápido. 
2. Crea dos archivos idéticos a Deposito.sol y Hackermalvado.sol.
3. Compila y despliega Deposito.sol, para más tarde hacer lo mismo con Hackermalvado.sol pasándole la dirección de Deposito como argumento del constructor.
4. Deposita fondos en deposito.sol utilizando mediante la funcion deposit
5. Cambia de address y ejecuta attack con 1 ether como parámetro, obteniendo así todos los fondos del contrato.
