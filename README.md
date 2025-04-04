# Emulador de Efeito Doppler na Modulação LoRa

## Introdução
Este repositório contém os códigos-fonte para realizar a emulação do efeito Doppler na modulação LoRa. O sistema recebe como entrada:
- Payload
- Fator de espalhamento (Spreading Factor)
- Largura de banda (Bandwidth)
- Doppler Shift
- Doppler Rate

## Passos para uso da ferramenta de emulação do efeito Doppler

O código base para a modulação foi utilizado a partir do repositório original [gr-lora_sdr](https://github.com/tapparelj/gr-lora_sdr), desenvolvido por Joaquin Tapparel. Portanto, inicialmente, siga o passo a passo para clonar o projeto e instalar o ambiente de desenvolvimento conforme descrito no repositório original.

### Clonando o repositório base e instalando dependências
```bash
# Clonar o repositório original
git clone https://github.com/tapparelj/gr-lora_sdr.git

# Acessar o diretório do projeto
cd gr-lora_sdr

# Seguir os passos de instalação conforme o repositório original
```

### Substituição dos arquivos
Após instalar o ambiente de desenvolvimento, baixe os arquivos deste repositório e substitua-os nas respectivas pastas do projeto base. A estrutura de diretórios é a seguinte:

```bash
gr-lora_sdr/
├── include/
│   ├── utilities.h
│   ├── modulate.h
├── lib/
│   ├── modulate_impl.cc
│   ├── modulate_impl.h
├── grc/
│   ├── lora_sdr_modulate.block.yml
├── python/
│   ├── lora_sdr/
│   │   ├── bindings/
│   │   │   ├── modulate_python.cc
│   │   │   ├── _utilities_python.cc
```

Certifique-se de substituir corretamente os arquivos mencionados acima para garantir o funcionamento adequado da emulação do efeito Doppler na modulação LoRa.

## Contribuição
Sinta-se à vontade para contribuir com melhorias para este projeto. Caso encontre problemas ou tenha sugestões, abra uma *issue* ou envie um *pull request*.

## Licença
Este projeto segue a mesma licença do repositório original [gr-lora_sdr](https://github.com/tapparelj/gr-lora_sdr). Consulte o repositório original para mais detalhes.

---

Caso precise de mais ajustes, me avise!

