Antes de que puedas autorizar un token de acceso personal o llave SSH, debes haber vinculado una identidad de SAML. Si eres miembro de una organización en donde está habilitado el SSO de SAML, puedes crear una identidad vinculada autenticándote en tu organización con tu IdP por lo menos una vez. Para obtener más información, consulta la sección "[Acerca de la autenticación con el inicio de sesión único de SAML](/authentication/authenticating-with-saml-single-sign-on/about-authentication-with-saml-single-sign-on)".

Después de que autorizas un token de acceso personal o llave SSH, estos se mantendrán autorizados hasta que se revoquen en alguna de las siguientes formas.
- Un propietario de empresa u organización revoca la autorización.
- Se te elimina de la organización.
- Se editan los alcances en un token de acceso personal o este se regenera.
- El token de acceso personal venció conforme a lo definido durante su creación.
