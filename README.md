# HOLA MUNDO! # 

class MainActivity : AppCompatActivity() {
    override fun onCreate(savedInstanceState: Bundle?) {
        super.onCreate(savedInstanceState)
        setContentView(R.layout.activity_main)

           Presentacion()
           Actualidad()
           Cnocimientos()
    }
//Attributes


  val nombre = "Franco Mauricio Muñoz Toledo"
    var edad = 28
    val carrera ="ingeniero en computación e informática"
    val universidad ="Andrés Bello"
    var desarrollador="FullStack Java"
    val lenguajes = arrayOf("HTML","PHP","JAVA","CSS","KOTLIN","SQL")



    private fun Presentacion() {
        println("Mi nombre es $nombre tengo $edad años, soy $carrera de la universidad $universidad y soy desarrollador $desarrollador")
    }
    private fun Actualidad() {
        desarrollador = "Android Kotlin"
        println("Me desempeño actualmente como desarrollador $desarrollador")

    }
    private fun Conocimientos(){
        println("Tengo conocimientos avanzados en los siguientes lenguajes: ${lenguajes[0]}, ${lenguajes[1]}, ${lenguajes[2]}, ${lenguajes[3]}, ${lenguajes[4]}, ${lenguajes[5]}")
    }
