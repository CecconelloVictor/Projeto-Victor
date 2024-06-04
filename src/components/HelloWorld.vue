<template>
  <div class="hello">
    <h1>{{ msg }}</h1> 

    <p>
Seja bem-vindo ao nosso escritório de advocacia. Estamos aqui para oferecer a você serviços jurídicos de qualidade, com dedicação, ética e comprometimento.
Nosso escritório é formado por advogados experientes e dedicados, prontos para representar seus interesses com excelência em diversas áreas do direito.
Estamos aqui para orientá-lo, defender seus direitos e ajudá-lo a alcançar seus objetivos jurídicos.
Nossos Serviços:
Oferecemos uma ampla gama de serviços jurídicos
Entre em Contato:
Telefone XXXXXXX
Se você precisa de assistência jurídica ou gostaria de agendar uma consulta, entre em contato conosco.
Agradecemos a sua visita e esperamos poder servi-lo em breve!
    </p>
       <ul>
      <li><a href="Link1" target="_blank" rel="noopener">Telefone 1 </a></li>
      <li><a href="Link2" target="_blank" rel="noopener">Telefone 2</a></li>
    </ul>
   
   </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
