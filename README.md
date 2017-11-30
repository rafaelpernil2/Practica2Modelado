# Practica2Modelado
Practica Atracciones Modelado



La empresa DIVERTIMENTO, S. A., tiene varios parques de atracciones repartidos por la geografía
nacional. Lo que más preocupa a esta empresa es la seguridad en algunas de las atracciones, ya
que un error mecánico podría producir daños materiales y humanos que plantearían serios
problemas para la empresa. Hoy por hoy sólo es posible detectar fallos en las atracciones cuando
los operarios encargados realizan actividades de mantenimiento. La empresa quiere
informatizar sus parques de atracciones y para ello ya ha decidido poner en marcha un proyecto
piloto cuyo objetivo será el de dotar a uno de sus parques de atracciones de un sistema de
detección automática de fallos en las atracciones.
En un primer momento se va a preparar el sistema para gestionar la Noria y la Montaña Rusa.
La noria tiene una serie de vehículos dotados cada uno de ellos de un detector gracias al cual se
sabe en cada momento si el vehículo está suficientemente bien anclado a la estructura metálica
de la noria. Si en un momento determinado se detectara pérdida de anclaje, el correspondiente
vehículo se lo comunicaría a la Central Receptora de Averías (CRA) y también a la atracción de
la que forma parte dicho vehículo. Así, en la próxima parada de dicha atracción se tendrá
constancia de que uno de sus vehículos ha solicitado revisión. Por su parte, en la montaña rusa
cada vagón está dotado de igual modo de un detector de anclaje con el vagón que lleva detrás.
Cada vagón en el caso de llevarlo detecta si existe suficiente anclaje con el vagón posterior y en
caso de falta de anclaje avisa a la CRA y a la atracción, en este caso la montaña rusa.
Cuando la CRA recibe un aviso, en el que se le indica el vehículo o vagón con posible avería y la
atracción de que se trata, busca inmediatamente un operario de mantenimiento disponible. En
caso de no haber ninguno libre, informa al componente en cuestión de que su petición no puede
ser atendida, así dicho componente emitirá una señal de solicitud de revisión hasta que su
petición le sea satisfecha.
Cada operario de mantenimiento tiene asignado un dispositivo gracias al cual recibe las posibles
averías a atender, independientemente de en qué zona del parque se encuentre, y que
almacena el número de avisos resueltos por el operario. Cuando la CRA demanda la revisión de
una posible avería y encuentra un operario de mantenimiento libre, le manda un mensaje a su
dispositivo indicándole la calle del parque en la que se encuentra la atracción y el número de
vehículo o vagón con posible avería. Automáticamente, el dispositivo del operario pasa a indicar
que ese operario se encuentra ocupado atendiendo una posible avería. Cuando el operario ha
terminado de supervisarla, indica a su dispositivo que ha quedado libre para la siguiente petición
de avería que reciba. A su vez dicho dispositivo informa a la CRA y al componente revisado. Dicho
componente avisará a su atracción de que la operación de mantenimiento solicitada ha
terminado para que ésta lo tenga en cuenta a la hora de poner la atracción en marcha de nuevo.
