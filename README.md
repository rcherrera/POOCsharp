# POOCsharp
La Programación Orientada a Objetos (POO) es un paradigma de programación que organiza el código en objetos (entidades con datos y comportamiento) que interactúan entre sí, en lugar de un enfoque lineal basado en funciones. Se basa en clases como plantillas para crear objetos, y se fundamenta en cuatro pilares clave: la abstracción, el encapsulamiento, la herencia y el polimorfismo.

Conceptos Fundamentales

**Objeto:**

Es una entidad que combina estado (datos o propiedades) y comportamiento (métodos o funciones). Por ejemplo, un objeto "coche" puede tener propiedades como "color" y "marca", y métodos como "acelerar" o "frenar".

[**Clase**](https://www.google.com/search?sca_esv=6b693d07bb019c16&sxsrf=AE3TifPtATA6TNaORuRON5ptoxMcINRGMg%3A1756358975342&q=Clase&sa=X&ved=2ahUKEwjf8MqG46yPAxWhmbAFHbYeDtEQxccNegUIiQEQAQ&mstk=AUtExfDzkPwVcROU1IM90hyY_7O_bj46pdA7zzwP_wYdmcuVg7As5k580gA-GYGpftDndRdAgXvCR9KnbwlYZypdLEE9CRHEeGzk4vcmZPHEgqaJayj23-Yl4witQ2067qZpFiPxKjku1yBM1J2G4UWLm9CJ5zpQfTYfqbFSZCNK-Qxd-KGaKIL9q37D7Nb9sjfAsjSBeiN2H-wG8DItxqWIwIEvgaJ9bqIvsSzXOYqVp_hhovrFGMGPox7TC6tzU18AaliMPgvsZdcYTpYj9Cuq_aro&csui=3)**:**

Es una plantilla o blueprint para crear objetos. Define las propiedades y métodos que los objetos de esa clase tendrán. Un "coche" es una clase, y un "coche rojo Ford Fiesta" es un objeto específico de esa clase.

**Atributos:**

Son las propiedades o características de un objeto. En el ejemplo del coche, el color y la marca serían atributos.

**Métodos:**

Son las funciones asociadas a los objetos que definen su comportamiento. El método "acelerar" es la acción que el objeto "coche" puede realizar.

Los Cuatro Pilares de la POO

**1.** [**Abstracción**](https://www.google.com/search?sca_esv=6b693d07bb019c16&sxsrf=AE3TifPtATA6TNaORuRON5ptoxMcINRGMg%3A1756358975342&q=Abstracci%C3%B3n&sa=X&ved=2ahUKEwjf8MqG46yPAxWhmbAFHbYeDtEQxccNegUI9QEQAQ&mstk=AUtExfDzkPwVcROU1IM90hyY_7O_bj46pdA7zzwP_wYdmcuVg7As5k580gA-GYGpftDndRdAgXvCR9KnbwlYZypdLEE9CRHEeGzk4vcmZPHEgqaJayj23-Yl4witQ2067qZpFiPxKjku1yBM1J2G4UWLm9CJ5zpQfTYfqbFSZCNK-Qxd-KGaKIL9q37D7Nb9sjfAsjSBeiN2H-wG8DItxqWIwIEvgaJ9bqIvsSzXOYqVp_hhovrFGMGPox7TC6tzU18AaliMPgvsZdcYTpYj9Cuq_aro&csui=3)**:**

Se enfoca en identificar y definir los atributos y métodos relevantes de un objeto, ignorando los detalles irrelevantes para un problema específico.

**2.** [**Encapsulamiento**](https://www.google.com/search?sca_esv=6b693d07bb019c16&sxsrf=AE3TifPtATA6TNaORuRON5ptoxMcINRGMg%3A1756358975342&q=Encapsulamiento&sa=X&ved=2ahUKEwjf8MqG46yPAxWhmbAFHbYeDtEQxccNegUI7wEQAQ&mstk=AUtExfDzkPwVcROU1IM90hyY_7O_bj46pdA7zzwP_wYdmcuVg7As5k580gA-GYGpftDndRdAgXvCR9KnbwlYZypdLEE9CRHEeGzk4vcmZPHEgqaJayj23-Yl4witQ2067qZpFiPxKjku1yBM1J2G4UWLm9CJ5zpQfTYfqbFSZCNK-Qxd-KGaKIL9q37D7Nb9sjfAsjSBeiN2H-wG8DItxqWIwIEvgaJ9bqIvsSzXOYqVp_hhovrFGMGPox7TC6tzU18AaliMPgvsZdcYTpYj9Cuq_aro&csui=3)**:**

Consiste en agrupar los datos (atributos) y los métodos que operan sobre esos datos en una sola unidad (la clase). Esto protege la información del objeto de accesos no autorizados y asegura que los datos solo se modifiquen a través de los métodos de la propia clase.

**3.** [**Herencia**](https://www.google.com/search?sca_esv=6b693d07bb019c16&sxsrf=AE3TifPtATA6TNaORuRON5ptoxMcINRGMg%3A1756358975342&q=Herencia&sa=X&ved=2ahUKEwjf8MqG46yPAxWhmbAFHbYeDtEQxccNegUI8gEQAQ&mstk=AUtExfDzkPwVcROU1IM90hyY_7O_bj46pdA7zzwP_wYdmcuVg7As5k580gA-GYGpftDndRdAgXvCR9KnbwlYZypdLEE9CRHEeGzk4vcmZPHEgqaJayj23-Yl4witQ2067qZpFiPxKjku1yBM1J2G4UWLm9CJ5zpQfTYfqbFSZCNK-Qxd-KGaKIL9q37D7Nb9sjfAsjSBeiN2H-wG8DItxqWIwIEvgaJ9bqIvsSzXOYqVp_hhovrFGMGPox7TC6tzU18AaliMPgvsZdcYTpYj9Cuq_aro&csui=3)**:**

Permite que una clase (hija) herede las propiedades y métodos de otra clase (padre), reduciendo la repetición de código y promoviendo la reutilización.

**4.** [**Polimorfismo**](https://www.google.com/search?sca_esv=6b693d07bb019c16&sxsrf=AE3TifPtATA6TNaORuRON5ptoxMcINRGMg%3A1756358975342&q=Polimorfismo&sa=X&ved=2ahUKEwjf8MqG46yPAxWhmbAFHbYeDtEQxccNegUI8QEQAQ&mstk=AUtExfDzkPwVcROU1IM90hyY_7O_bj46pdA7zzwP_wYdmcuVg7As5k580gA-GYGpftDndRdAgXvCR9KnbwlYZypdLEE9CRHEeGzk4vcmZPHEgqaJayj23-Yl4witQ2067qZpFiPxKjku1yBM1J2G4UWLm9CJ5zpQfTYfqbFSZCNK-Qxd-KGaKIL9q37D7Nb9sjfAsjSBeiN2H-wG8DItxqWIwIEvgaJ9bqIvsSzXOYqVp_hhovrFGMGPox7TC6tzU18AaliMPgvsZdcYTpYj9Cuq_aro&csui=3)**:**

Significa "muchas formas". Permite que objetos de diferentes clases respondan de manera propia a la misma orden o método. Por ejemplo, al llamar al método "emitir sonido", un objeto "perro" ladraría y un objeto "gato" maullaría.

Beneficios de la POO

**Reutilización de código:**

La herencia permite usar código ya escrito en nuevas clases, ahorrando tiempo y esfuerzo.

**Organización del código:**

Los programas son más fáciles de entender y mantener, ya que el código está organizado en objetos lógicos y coherentes.

**Facilidad de crecimiento:**

Se pueden añadir nuevos objetos o funcionalidades al sistema de forma más sencilla.

**Manejo de errores:**

El encapsulamiento ayuda a proteger el estado interno de los objetos, lo que reduce la posibilidad de errores inesperado
