def verificar_acl(numero):

    numero = int(numero)

    if 1 <= numero <= 99:

        return "ACL Estándar"

    elif 100 <= numero <= 199:

        return "ACL Extendida"

    else:

        return "No corresponde a una lista de acceso."





numero = input("Ingrese la ACL IPv4: ")



tipo = verificar_acl(numero)

print("Tipo de ACL:", tipo)



