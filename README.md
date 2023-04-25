# vlibras

Lib React que ajuda você a implementar o VLibras no seu site.

Esse componente segue os padrões fornecidos na [documentação do vlibras](https://www.vlibras.gov.br/doc/widget/index.html).

> Os surdos enfrentam bastante dificuldade para ler, escrever e se comunicar na língua oral do seu país. Dessa forma, para tentar reduzir esses problemas, o objetivo da ferramenta computacional de código aberto, denominada VLibras Widget, consiste em traduzir conteúdos do Português Brasileiro para a Língua Brasileira de Sinais (LIBRAS), tornando websites acessíveis a pessoas surdas. -- [Visão geral vlibras](https://www.vlibras.gov.br/doc/widget/introduction/overview.html)

## Instalação

```typescript
  npm i @moreiraste/react-vlibras
```

## Como usar

React (App.js)

```typescript
import VLibras from '@moreiraste/react-vlibras'

function App() {
  return (
    <div>
      <VLibras />
    </div>
  )
}

export default App
```

**Parametros**

Você pode usar a propriedade `forceOnload` para forçar que o VLibras seja carregado a partir de decisões assíncronas, ja que por padrão ele é executado no evento `onload`.

```typescript
import VLibras from './index'

function App() {
  return (
    <div className="App">
      <VLibras forceOnload={true} />
      <header className="App-header">
        <h1>Teste</h1>
      </header>
    </div>
  )
}

export default App
```

## Resultado

![Rsultado 1](/public/assets/result1.png)

![Rsultado 2](/public/assets/result2.png)


