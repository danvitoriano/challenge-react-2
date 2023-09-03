# Ajustar o tamanho da imagem com base em um prop

Neste exemplo, o Avatar recebe um prop de tamanho numérico que determina a largura e altura do <img>. O prop de tamanho é definido como 40 neste exemplo. No entanto, se você abrir a imagem em uma nova guia, notará que a própria imagem é maior (160 pixels). O tamanho real da imagem é determinado pelo tamanho do thumbnail que você está solicitando.

Altere o componente Avatar para solicitar o tamanho da imagem mais próximo com base no prop de tamanho. Especificamente, se o tamanho for inferior a 90, passe 's' (“pequeno”) em vez de 'b' (“grande”) para a função getImageUrl. Verifique se suas alterações estão funcionando renderizando avatares com valores diferentes do prop de tamanho e abrindo imagens em uma nova guia.
