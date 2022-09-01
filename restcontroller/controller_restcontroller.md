## @controller

es una clase responsable de:

* procesar las peticiones entrantes de **REST API.**
* preparar el modelo.
* retornar la vista a ser renderizada como respuesta.

**@controller** y **@RestController** son las anotaciones que se usan
para denotar una clase controller permiten que Spring las use como un servicio
RESTful durante las ejecucion.


@controller es un tipo de @Component que permite ser reconocida como un componente 
administrado por Spring.
@Controller



´´´
@Controller
@ResponseBody
@RequestMapping("/api/tree")
public class TreeController {

    @Autowired
    private TreeRepository repository;
 
    @GetMapping("/{id}")
    public Tree getTreeById(@PathVariable int id) {
        return repository.findById(id);
    }
  
    @GetMapping
    public Tree getTreeById(@RequestParam String name, 
                            @RequestParam int age) {
        return repository.findFirstByCommonNameIgnoreCaseAndAge(name, age);
    }
}


´´´


https://stackabuse.com/controller-and-restcontroller-annotations-in-spring-boot/

