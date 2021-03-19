# referencial


Repositorio para guardar documentacao de referencias

-------------------------------------------------------------------------------------------------------------------------------------------------
Comandos git : https://githowto.com/pt-BR/amending_commits

---------------------------------------------------------------------------------------------------------------------------------------------------
REGEX : http://aprenda.vidageek.net/aprenda/regex

---------------------------------------------------------------------------------------------------------------------------------------------------

Injetar propriedade de teste spring

@ActiveProfiles("test")
@SpringBootTest
@TestInstance(TestInstance.Lifecycle.PER_CLASS)
@ExtendWith(SpringExtension.class)
@EnableAutoConfiguration

ou

@ExtendWith(SpringExtension.class)
@TestPropertySource(locations="classpath:application.properties")
