Cloned this because I'm a fan of the bean's design, and still have a handful in my toolbox.

Bean development has become a bit convoluted since Punchthrough has End-Of-Lifed the Beans.

Recent versions of MacOS are incompatible with the BeanLoader, 
so one has to keep an old instance of MacOS around to push your revisions to the bean.

The iOS Beanloader is brilliant, but depends on Punchthrough's web based compiler environment,
an iffy situation for an EOLed product, and the linked arduino libs in the compiler environment
cannot be modified. This was specifically a problem when I tried to use the FreeRTOS lib.
see https://arduino.stackexchange.com/questions/66073/freertos-tasks-never-run-on-lightblue-bean
for more on that.
