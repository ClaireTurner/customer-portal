---

copyright:

  years: 1994, 2019

lastupdated: "2019-02-25"

keywords: IBM Cloud user, user name, portal account, cp FAQs 


subcollection: customer-portal

---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:tip: .tip}
{:screen: .screen}
{:new_window: target="_blank"}
{:faq: data-hd-content-type='faq'}


# Preguntas más frecuentes
{: #bicpfaq}

## ¿Cómo puedo recuperar mis credenciales para el portal de clientes?
{: #bicp_retcreds}
{: faq}

Si utiliza IBMid para la autenticación, cuando realice su primer pedido o cuando se le añada como usuario a una cuenta, recibirá un correo electrónico que tiene un enlace para iniciarle a su IBMid. Si pierde u olvida el nombre de usuario o la contraseña, vaya al [perfil de IBMid ![Icono de enlace externo](../icons/launch-glyph.svg)](https://www.ibm.com/account/profile){:new_window} y restablezca o recupere la contraseña. Se le solicitará que especifique información específica, lo que puede incluir la creación de respuestas a las preguntas de seguridad.

Si no utiliza IBMid para la autenticación, cuando realice su primer pedido o cuando se le añada como usuario a una cuenta de [portal de clientes ![Icono de enlace externo](../icons/launch-glyph.svg)](https://control.softlayer.com/){:new_window}, recibirá un correo electrónico con su nombre de usuario y su contraseña inicial para empezar en el portal de clientes. Asegúrese de cambiar la contraseña después de iniciar sesión por primera vez editando su perfil de usuario.

Si olvida la contraseña tras iniciar sesión, utilice la característica **Contraseña olvidada** que está disponible en la pantalla de inicio de sesión del portal de clientes. Se le solicitará que especifique información específica, incluido un conjunto de pregunta que ha especificado al editar el perfil de usuario.

Si olvida su nombre de usuario, póngase en contacto con el administrador de la cuenta o con el usuario maestro, quien puede recuperar su nombre de usuario. Si usted es el administrador o el usuario maestro de la cuenta, póngase en contacto con el Soporte para obtener más ayuda.

## ¿Qué es el IBMid?
{: #bicp_whatisibmid}
{: faq}

Las cuentas nuevas requieren IBMid para la autenticación. Las cuentas existentes seguirán utilizando el nombre de usuario y la contraseña de SoftLayer para la autenticación hasta que ejecute la herramienta de migración para cambiar a un IBMid. Su cuenta de SoftLayer tiene un usuario maestro, que tendrá autorización para añadir más usuarios dentro de esa misma cuenta. 

## ¿Cómo puedo enlazar una cuenta de SoftLayer existente?
{: #bicp_linkbmxacct}
{: faq}

Si es el usuario maestro de la cuenta de SoftLayer, inicie sesión en el portal de clientes y pulse **Enlazar una cuenta** en la cabecera. Consulte [Cómo enlazar cuentas de usuario de IBMid](/docs/account?topic=account-unifyingaccounts#unifyingaccounts) para obtener más información.

## ¿Tengo que ser un usuario existente de {{site.data.keyword.Bluemix_notm}} para enlazar cuentas?
{: #bicp_bmxusertolink}
{: faq}

No. Puede crear una cuenta nueva de {{site.data.keyword.Bluemix_notm}} o enlazar una cuenta de Prueba o de Pago según uso existente de {{site.data.keyword.Bluemix_notm}}.

## ¿Cómo funciona la autenticación de dos factores?
{: #bicp_2fa}
{: faq}

No hay impacto en la configuración de la autenticación de dos factores (2FA) a nivel de cuenta. 2FA no se realiza por IBMid, sino por cuenta. Cuando un IBMid se asocie con muchas cuentas, y pueda cambiar entre ellas, debe confirmar su identidad cada vez que cambie a una cuenta distinta que necesite 2FA. Esto es cierto incluso aunque la cuenta anterior y la cuenta nueva estén configuradas con el mismo mecanismo de 2FA.

Para obtener más información sobre IBMid con 2FA, consulte [Uso de la autenticación de multifactores en cuentas enlazadas](/docs/account?topic=account-2fa#2fa).

## ¿Quién puede enlazar cuentas?
{: #bicp_wholinkaccts}
{: faq}

Solo los usuarios maestros de la infraestructura de {{site.data.keyword.BluSoftlayer_notm}} pueden enlazar cuentas de SoftLayer y de {{site.data.keyword.Bluemix_notm}}. El correo electrónico de un usuario maestro también debe estar asociado al propietario principal de la cuenta de {{site.data.keyword.Bluemix_notm}} que se está enlazando.

## ¿Qué utilizaré para iniciar sesión en cada consola?
{: #bicp_logineachport}
{: faq}

La facturación de la cuenta está enlazada y puede moverse de forma sencilla entre las cuentas de SoftLayer y {{site.data.keyword.Bluemix_notm}}, pero sus identidades de cuenta permanecerán separadas.

* Si la cuenta no utiliza IBMid para la autenticación, siga utilizando el ID de SoftLayer para los productos y servicios de SoftLayer, y utilice IBMid para los productos y servicios de {{site.data.keyword.Bluemix_notm}}.

* Si la cuenta utiliza IBMid para la autenticación, utilice el IBMid para acceder a las cuentas de SoftLayer y {{site.data.keyword.Bluemix_notm}}.

## ¿Por qué obtengo un error al intentar iniciar sesión con mi nombre de usuario de SoftLayer?
{: #bicp_SLloginerror}
{: faq}

Tras cambiar a un IBMid, si inicia sesión en el portal de clientes con el nombre de usuario de la infraestructura de {{site.data.keyword.BluSoftlayer_notm}}, se mostrará el error "Se han proporcionado credenciales de inicio de sesión no válidas". Tras cambiar a un IBMid, ya no puede iniciar sesión en el portal de clientes con su nombre de usuario de la infraestructura de {{site.data.keyword.BluSoftlayer_notm}}. Debe pulsar **Iniciar sesión con IBMid** en el diálogo Inicio de sesión de cuenta.

## ¿Por qué obtengo un error al intentar iniciar sesión con mi IBMid?
{: #bicp_IBMidloginerror}
{: faq}

Al iniciar sesión con su IBMid, se mostrará el error "No hemos reconocido este IBMid o correo electrónico". Asegúrese de especificar una dirección de correo electrónico completa. Asegúrese también de que no está utilizando el nombre de usuario de la infraestructura de {{site.data.keyword.BluSoftlayer_notm}}.

## ¿Pueden acceder los miembros del equipo de infraestructura de {{site.data.keyword.BluSoftlayer_notm}} a mi cuenta enlazada?
{: #bicp_linkgiveteamaccess}
{: faq}

Debe invitarles a {{site.data.keyword.Bluemix_notm}}. En la consola de {{site.data.keyword.Bluemix_notm}}, pulse **Gestionar** > **Cuenta** > **Usuarios**. Después de seleccionar un grupo de recursos, puede añadir miembros del equipo de infraestructura de {{site.data.keyword.BluSoftlayer_notm}}. Puede que tenga que iniciar sesión en el portal de clientes para poder enviar invitaciones. {{site.data.keyword.Bluemix_notm}} obtiene la lista de usuarios de la infraestructura de {{site.data.keyword.BluSoftlayer_notm}}, y a continuación puede seleccionar qué usuarios invitar a la cuenta de {{site.data.keyword.Bluemix_notm}}.

## ¿Dónde está mi correo electrónico para completar el cambio a IBMid?
{: #bicp_ibmidswitchemail}
{: faq}

Si ha seguido el asistente para cambiar a IBMid y no ha recibido el correo electrónico, el envío del correo electrónico con su código de registro puede tardar desde unos minutos a unas horas. Puede volver a la página **Editar perfil de usuario** en el portal de clientes y pulsar **Reenviar correo electrónico** para intentarlo de nuevo.

## ¿Tendré acceso root completo a mi cuenta?
{: #bicp_fullrootaccaccess}
{: faq}

Los usuarios maestros, y aquellos con permisos de administrador, tienen acceso completo como usuario root a las cuentas del portal de clientes y de la API. Los usuarios sin permisos de administrador tienen la accesibilidad controlada por aquellos con roles de administración. Estos permisos los pueden actualizar administradores desde el portal de clientes [editando un perfil de usuario](/docs/customer-portal?topic=customer-portal-cp_edituserprofile#cp_edituserprofile). Sin permisos de administrador, puede editar el perfil de usuario en el portal de clientes pulsando su nombre de usuario en el panel superior.

## ¿Puedo enlazar una cuenta de suscripción de {{site.data.keyword.Bluemix_notm}}?
{: #bicp_linkbmxsubacct}
{: faq}

Todas las cuentas enlazadas en {{site.data.keyword.Bluemix_notm}} deben ser cuentas de Prueba o de Pago según uso. 

## ¿Cómo puedo desenlazar mi cuenta?
{: #bicp_unlinkacct}
{: faq}

Después de enlazar las cuentas, estas no se podrán desenlazar.


## ¿Qué es mi perfil de empresa y dónde puedo encontrarlo?
{: #bicp_whatfindcompprof}
{: faq}

El perfil de empresa es la información que se envía en el momento de crear la cuenta e incluye un contacto principal para la empresa, junto con el nombre, la dirección y el número de teléfono de la empresa. Esta información se utiliza por diversos motivos y se debe mantener siempre actualizada. Para ver el perfil de la empresa para su cuenta o para solicitar cambios, consulte [Actualización del perfil de la empresa](/docs/customer-portal?topic=customer-portal-cp_updateprofile#cp_updateprofile).

## ¿Dónde puedo encontrar las contraseñas de mi dispositivo y del software?
{: #bicp_devswpw}
{: faq}

Las contraseñas del dispositivo y del software se almacenan en dos ubicaciones dentro del portal de clientes. Para recuperar las credenciales del dispositivo, incluidos el nombre de usuario y la contraseña del administrador y del usuario root para {{site.data.keyword.baremetal_short}} y {{site.data.keyword.virtualmachinesshort}}, consulte [Interactuar con un dispositivo en la vista de instantánea](/docs/vsi?topic=virtual-servers-interacting-with-a-device-in-snapshot-view#interacting-with-a-device-in-snapshot-view). Para ver y recuperar rápidamente las credenciales del software que se rastrean manualmente utilizando el portal de clientes, consulte [Gestión el acceso a dispositivos](/docs/vsi?topic=virtual-servers-managing-device-access#managing-device-access).

## ¿Cómo mantengo mis datos web sincronizados?
{: #bicp_webdatasync}
{: faq}

Aunque es responsable de mantener la coherencia de datos entre los servidores reales, {{site.data.keyword.BluSoftlayer_full}} proporciona una red privada que puede utilizar para sincronizar sin incurrir en cargos de uso.

## ¿Qué es el Event Management System?
{: #bicp_whatisems}
{: faq}

Event Management System es un conjunto de herramientas que optimiza la forma en que {{site.data.keyword.BluSoftlayer_full}} comparte la información con los usuarios sobre problemas de infraestructura no planificados y sucesos próximos de mantenimiento planificados. Utiliza alertas por correo electrónico basadas en suscripción y con destino para estos incidentes para compartir el tipo de suceso que se haya producido. Proporciona a los usuarios suscritos detalles sobre el impacto general del suceso y un estado actual del incidente en curso no planificado (UIP).

## ¿Puedo cancelar un dispositivo?
{: #bicp_candev}
{: faq}

Puede cancelar un dispositivo en cualquier momento a través del portal de clientes. Consulte [Cancelar un dispositivo](/docs/vsi?topic=virtual-servers-managing-virtual-servers#managing-virtual-servers) para obtener más información sobre la finalización de una solicitud de cancelación.
