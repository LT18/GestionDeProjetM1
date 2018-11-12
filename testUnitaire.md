# Les tests unitaires

Un *test unitaire* est un procédé permettant de s'assurer du bon fonctionnement d'une unité de programme.

## Quelques framworks

*CUnit
*CPPUnit
*JUnit

## Exemple de code avec JUnit (Java)

public class MaClasseTest extends TestCase{

  public void testCalculer() throws Exception {

    assertEquals(2,MaClasse.calculer(1,1));
  }
}
