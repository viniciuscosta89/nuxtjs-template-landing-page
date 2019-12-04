<template>
  <main>
    <BigBanner
      img="https://www.baressp.com.br/site_php/cursos_landing/images/header/header.jpg"
    />
    <Separator />
    <section class="description bg-bege">
      <div class="container flex flex-wrap mx-auto py-10 px-8 xl:px-0">
        <div
          class="flex-grow lg:w-1/2 lg:pr-4 mb-4 lg:mb-0 text-center lg:text-left"
        >
          <img
            class="inline-block max-w-full"
            src="https://www.baressp.com.br/site_php/cursos_landing/images/principal/curso-bartender-flair-para-bares-1.jpg"
            alt="Bartender"
          >
        </div>

        <div class="flex-grow lg:w-1/2 lg:pl-4 mb-4 lg:mb-0">
          <h2 class="font-bold text-2xl mb-4">
            Curso bartender flair para bares
          </h2>
          <p class="mb-4">
            O <strong>curso de bartender flair para bares</strong> ainda é uma
            novidade, apesar de a técnica de bartender flair estar cada dia mais
            presente em bares modernos e nos eventos mais badalados e
            prestigiados da atualidade. Bartender é o profissional encarregado
            do preparo de bebidas, drinks e coquetéis nos bares e festas.
            Diferente do barman (“homem do bar”, em tradução livre), o bartender
            é um termo que pode ser utilizado para pessoas de ambos os sexos e
            significa “atendente do bar”.
          </p>
          <p class="mb-4">
            Já a palavra flair se refere a uma técnica de movimentos próximos ao
            malabarismo, indicando, assim, que um bartender pode preparar os
            drinks com agilidade de forma artística, o que entretém e diverte os
            clientes enquanto esperam que o drink pedido fique pronto. Em um
            <strong>curso de bartender flair para bares</strong>, o profissional
            não só aprende técnicas de malabares e jogos com as taças e
            utensílios disponíveis no bar como também aprofunda e aperfeiçoa
            seus conhecimentos no preparo de drinks, incluindo aulas sobre o
            teor alcoólico das bebidas, técnicas para cortes de frutas e outros
            ingredientes para decoração, história das marcas das bebidas
            servidas, sua origem, curiosidades e muito mais.
          </p>
          <p class="mb-4">
            Para muitos donos de casas noturnas, vale a pena procurar por um bom
            <strong>curso de bartender flair para bares</strong>, pois garante
            que seus funcionários desempenhem o melhor serviço de entretenimento
            para os clientes, transformando o atendimento em um diferencial do
            negócio.
          </p>
        </div>
      </div>
    </section>

    <Gallery />

    <section class="description bg-bege">
      <div class="container flex flex-wrap mx-auto py-10 px-8 xl:px-0">
        <div
          class="flex-grow lg:w-1/2 lg:pr-4 mb-4 lg:mb-0 text-center lg:text-left"
        >
          <img
            class="inline-block max-w-full"
            src="https://www.baressp.com.br/site_php/cursos_landing/images/principal/curso-bartender-flair-para-bares-5.jpg"
            alt="Bartender"
          >
        </div>

        <div class="flex-grow lg:w-1/2 lg:pl-4 mb-4 lg:mb-0">
          <h2 class="font-bold text-2xl mb-4">
            Diferenciais do curso de bartender flair para bares
          </h2>
          <p class="mb-4">
            Antes de fazer um
            <strong>curso de bartender flair para bares</strong>, o profissional
            deve saber se possui algumas habilidades básicas, que farão dele um
            bartender flair talentoso e prestativo, tornando o curso proveitoso
            e vantajoso para sua carreira. São algumas delas:
          </p>

          <ul class="list-disc list-inside mb-4">
            <li class="mb-2">
              Boa aparência, prezando pela higiene pessoal, bons modos e
              elegância;
            </li>
            <li class="mb-2">
              Capacidade de lidar com o público;
            </li>
            <li class="mb-2">
              Boa resistência e disposição física;
            </li>
            <li class="mb-2">
              Falar alto e claro, ter boa dicção e, se possível, ter algum
              conhecimento em inglês e outras línguas estrangeiras;
            </li>
            <li class="mb-2">
              Ter agilidade e bons reflexos;
            </li>
            <li class="mb-2">
              Capacidade de trabalhar sob pressão;
            </li>
            <li class="mb-2">
              Ser muito organizado;
            </li>
            <li class="mb-2">
              Ser detalhista;
            </li>
            <li class="mb-2">
              Ter boa memória;
            </li>
            <li class="mb-2">
              Ser agradável e muito educado com clientes e colegas de trabalho.
            </li>
          </ul>

          <p class="mb-4">
            Em virtude do grande sucesso e procura do bartender flair, o mercado
            de trabalho está cada vez mais aberto a esse profissional. As
            possibilidades de trabalho vão desde bares, casas noturnas, casas de
            show, festas e eventos a cruzeiros e serviços internacionais. Tudo
            isso somado ao fato de que um bartender habilidoso geralmente é bem
            pago pelos seus serviços. Fazer um
            <strong>curso de bartender flair para bares</strong> é uma opção
            vantajosa para aqueles que desejam seguir carreira na área, ou até
            mesmo para o bartender que quer se especializar e aumentar sua
            atuação nas mais variadas propostas de trabalho.
          </p>
        </div>
      </div>
    </section>

    <BannerText />
    <Localization />
    <Separator />
  </main>
</template>

<script>
import BigBanner from '~/components/BigBanner'
import Separator from '~/components/Separator'
import Gallery from '~/components/Gallery'
import BannerText from '~/components/BannerText'
import Localization from '~/components/Localization'

export default {
  components: {
    BannerText,
    BigBanner,
    Gallery,
    Separator,
    Localization
  }
}
</script>

<style lang="scss" scoped>
.bg-bege {
  background-color: #ece9e2;
}
</style>
