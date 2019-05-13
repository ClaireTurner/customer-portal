---

copyright:

  years: 1994, 2019

lastupdated: "2019-05-03"

keywords: SoftLayer account, new users, IBM Cloud account

subcollection: customer-portal 

---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:tip: .tip}
{:screen: .screen}
{:new_window: target="_blank"}


# Guía de aprendizaje de iniciación
{: #getting-started}

En esta guía de aprendizaje, le guiaremos por el proceso de ejecución y uso de su cuenta de SoftLayer para que pueda comenzar a solicitar y a gestionar los recursos de infraestructura.
{:shortdesc}

## Antes de empezar
{: #prereqs}

Necesita una cuenta de [{{site.data.keyword.Bluemix}} ![Icono de enlace externo](../icons/launch-glyph.svg "Icono de enlace externa")](https://cloud.ibm.com){:new_window}. Inicie sesión en el portal de clientes con sus credenciales de IBMid. La mayoría de los usuarios nuevos utilizan [IBMid](/docs/account?topic=account-unifyingaccounts#switchtoIBMid) para su autenticación.

Si no utiliza un IBMid para la autenticación para iniciar sesión en la cuenta, inicie sesión en el portal de clientes con sus credenciales exclusivas de infraestructura de {{site.data.keyword.BluSoftlayer_notm}}.
{: tip}

## Paso 1. Configurar la cuenta
{: #account-setup}

La configuración de la cuenta incluye la verificación de la información de contacto de la cuenta y los detalles de facturación:
 * Para verificar los detalles de contacto de la empresa, vaya a **Cuenta** > **Gestionar** > **Contactos de empresa**. La información de contacto de la empresa de la cuenta se utilizará para notificarle sobre los problemas o los cambios en su cuenta.
 * Para verificar los detalles del perfil de la empresa, vaya a **Cuenta** > **Gestionar** > **Perfil de empresa**. La información de perfil de la empresa contiene detalles sobre el titular de la cuenta principal.
 * Para verificar los detalles de facturación, vaya a **Cuenta** > **Facturación** > **Método de pago**. El método de pago mensual es la tarjeta de crédito facturada de forma recurrente para los pagos asociados con la cuenta.

## Paso 2. Añadir usuarios y asignar permisos
{: #users-permissions}

Para añadir usuarios a la cuenta y establecer permisos iniciales, vaya a **Cuenta** > **Usuarios**.
 * Para invitar a usuarios a los recursos de plataforma y de infraestructura de su cuenta basados en los permisos específicos que asigne, pulse **Invitar a usuarios**. Se le dirigirá entonces a la IU de {{site.data.keyword.Bluemix_notm}} Identity and Access Management (IAM) para invitar a usuarios y asignar el acceso. Consulte [Invitación a usuarios](/docs/iam?topic=iam-iamuserinv#iamuserinv) para obtener más información.
 * Para añadir usuarios que solo tengan acceso VPN, pulse **Añadir usuario solo VPN**. Escriba la información personal, configure los permisos del portal y establezca el acceso de dispositivo para el usuario.

Al establecer permisos de infraestructura en la invitación inicial, opte por uno de los tres conjuntos de permisos: Solo visualización, Usuario básico, Superusuario. Cuando los usuarios acepten la invitación, podrá personalizar su acceso editando sus permisos de portal. Para obtener más información, consulte [Permisos de infraestructura](/docs/iam?topic=iam-infrapermission#infrapermission).
{: tip}

## Paso 3. Habilitar el acceso a la red privada de la infraestructura de {{site.data.keyword.Bluemix_notm}}
{: #enable-private-network}

La red privada de la infraestructura de {{site.data.keyword.Bluemix_notm}} se ofrece a los usuarios y a los dispositivos de forma gratuita. Todo el ancho de banda de la red privada no se mide y es gratuito. La red privada ofrece muchas ventajas, entre las que están las siguientes:
  * Réplica de los entornos de dispositivos a otros centros de datos para la migración tras error
  * Accesibilidad del sistema frontal a los servidores de base de datos
  * Acceso y gestión seguros a sus sistemas

Para habilitar el acceso de usuario a la red privada, edite el acceso VPN en el portal de clientes:
  1. Seleccione **Cuenta** > **Acceso VPN** desde la barra de menús.  
  2. Pulse el enlace en la columna Acceso a VPN.
  3. Seleccione una opción desde el menú **Tipo de VPN** y pulse **Guardar**.  

Para los usuarios de cuentas que utilizan la autenticación de IBMid, se utilizará el nombre de usuario de VPN de SoftLayer para el acceso a VPN. El nombre de usuario de VPN está definido en el perfil de usuario. El nombre de usuario de VPN es distinto del nombre de usuario que tiene como valor predeterminado la dirección de correo electrónico y el ID de la cuenta de IBMid.
{: tip}

Para obtener más información sobre cómo utilizar una conexión VPN, consulte [Acerca de VPN](/docs/infrastructure/iaas-vpn?topic=VPN-about-iaas-vpn#about-iaas-vpn).

## Paso 4. Suscribirse a las notificaciones
{: #get-notified}

Para obtener una notificación sobre los problemas del sistema y sobre los sucesos de mantenimiento planificados, puede suscribirse a notificaciones mediante el Event Management System. Al crear una cuenta o si se le ha añadido a una, se cancelará su suscripción a las notificaciones de forma predeterminada.

Acceda al Event Management System en el portal de clientes para elegir a qué notificaciones desea suscribirse:
  1. Seleccione **Cuenta** > **Gestionar** > **Suscripciones** en la barra de menús.
  2. Pulse una suscripción específica de la lista.
  3. Seleccione **Sí** en la columna Suscrito.
  4. Pulse **Ver todas las suscripciones** para volver a la lista de suscripciones disponibles y suscribirse a otros tipos si es necesario.

## Pasos siguientes
{: #next-steps}

Una vez configurada la cuenta, vaya al [catálogo de {{site.data.keyword.Bluemix_notm}} ![Icono de enlace externo](../icons/launch-glyph.svg)](https://{DomainName}/catalog/?category=infrastructure){:new_window} y empiece a solicitar dispositivos.
