<template>
    <v-container>
        <div v-for="item in lista" :key="item">
            <CardPet 
                :imagem="item.img" 
                :titulo="item.titulo" 
                :texto="item.texto"
            />
        </div>
    </v-container>
</template>

<script>
import CardPet from '../components/CardPet.vue'
export default {
    name: 'HomeView',
    components: {
        CardPet 
    },
    data() {
        return {
            lista: [
                {
                    img: "https://i.pinimg.com/originals/d2/4c/27/d24c27f438b9cc65bf2a943f179c6d85.jpg",
                    titulo: "American Staffordshire Terrier",
                    texto: "American Staffordshire Terrier, também conhecido como AmStaff, é uma raça de cães oriunda dos Estados Unidos. Relativamente recente, a raça é vista como uma remodelagem do Pit Bull. Por consequência o amstaff também é parente de uma outra raça, de origem inglesa e remota, a staffordshire bull terrier"
                },
                {
                    img: "https://yata-apix-df8ee382-52d2-486a-a3ca-22e996ff8a32.s3-object.locaweb.com.br/8a0adf7de7f44c00816df5b3ae6d2d4f.png",
                    titulo: "Pit Monster",
                    texto: "Pit Monster, Monster ou Brazilian Pit Monster é uma recente raça de cães brasileira, ainda em fase de aperfeiçoamento.A raça já é reconhecida por alguns kennel clubes no Brasil"
                },
                {
                    img: "https://images.vectorhq.com/images/previews/12b/american-bully-psd-455494.png",
                    titulo: "American Bully",
                    texto: "American Bully é uma raça de cães de companhia originária dos Estados Unidos.Foi reconhecida oficialmente pelo United Kennel Club em julho de 2013.Há controvérsias em relação à quais raças participaram na formação do American Bully."
                },
                {
                    img: "https://thumbs.dreamstime.com/b/dog-white-background-chocolate-pit-bull-terrier-charming-205069993.jpg",
                    titulo: "Red nose",
                    texto: "Red Nose é um termo usado para denominar cães com narinas de coloração vermelho-fígado.O termo surgiu entre os criadores de Pit Bull, mas a coloração está presente em diversas raças caninas, como por exemplo no pointer inglês, american bully, dogue de bordeaux, braco alemão e etc"
                }
            ]
        }
    }

}
</script>

<style>
</style>