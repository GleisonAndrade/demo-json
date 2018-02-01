# demo-json
Lista de produtos json para exemplo

Json gerado em https://www.json-generator.com/

[
  '{{repeat(20)}}',
  {
  id: '{{index(1)}}',
  descricao: 'Produto json ' + '{{index()}}',
  preco: '{{floating(1000, 1000000)}}',
  tipo: '{{random("tipo1", "tipo2", "tipo3")}}'
  }
]
