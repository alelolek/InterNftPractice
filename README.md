# Proyecto de Colección de NFTs con Funcionalidad de Interoperabilidad entre Cadenas

¡Bienvenidos a mi último proyecto! Se trata de una colección de NFTs diseñada especialmente para nuestra comunidad. Hemos elegido la popular red Polygon (Mumbai) como blockchain principal para esta iniciativa. Con el objetivo de atender a nuestros usuarios que poseen fondos en la red Ethereum (Goerli), hemos implementado una funcionalidad de interoperabilidad entre cadenas. Esto significa que los usuarios pueden realizar compras en la red Ethereum y luego tener sus NFTs acuñados en Polygon a través de un proceso fluido.

## Funcionalidades principales

- Los usuarios pueden comprar NFTs en la red Ethereum y tenerlos acuñados en Polygon.
- Utilizamos el token USDC como forma de pago inicial, pero los usuarios deben intercambiarlo por nuestro token del proyecto, MiPrimerToken, en un DEX como UNISWAP.
- Hemos creado un pool de liquidez en UNISWAP para facilitar el intercambio de USDC por MiPrimerToken.
- Nuestro proyecto utiliza contratos y middleware de Open Zeppelin Defender para garantizar la seguridad y eficiencia de las transacciones.
- Las imágenes y metadatos de los NFTs se almacenan en IPFS para una visualización y transferencia eficiente.

## Componentes clave

- **Token ERC20 (MiPrimerToken):** Nuestro token ERC20 personalizado, que sirve como la principal forma de pago para adquirir los NFTs.
- **NFT ERC721 (Colección de Cuyes):** Hemos creado una colección de NFTs que presenta adorables cuyes, los cuales los usuarios podrán adquirir.
- **Contrato de Compra y Venta de NFTs (Public Sale):** Este contrato actúa como interfaz para que los usuarios puedan comprar NFTs. Los usuarios pueden depositar MiPrimerToken en este contrato en la red Goerli para adquirir NFTs en la red Mumbai. Open Zeppelin Defender facilita la comunicación entre el contrato de Compra y Venta y el contrato de NFTs.
- **Stablecoin USDC:** Este contrato representa el token USDC en la red Goerli y proporciona los fondos iniciales para las operaciones de compra.

## Herramientas utilizadas

- Open Zeppelin Defender (Middleware): Utilizamos Open Zeppelin Defender para transmitir transacciones y automatizar procesos, garantizando la seguridad y eficiencia de nuestro proyecto.
- IPFS: Nuestro proyecto utiliza IPFS (Sistema de Archivos Interplanetarios) para almacenar imágenes y metadatos de los NFTs. Esto nos permite acceder a la información necesaria para visualizar y transferir los NFTs de manera eficiente.

Con este conjunto de contratos y herramientas, estamos emocionados de lanzar nuestra colección de NFTs y brindar a nuestra comunidad una experiencia excepcional en el mundo de los activos digitales.
