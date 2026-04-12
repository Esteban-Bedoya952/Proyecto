using System;

class Program
{
    static void Main(string[] args)
    {
        // datos
        Console.WriteLine("=== SISTEMA DE CLASIFICACIÓN DE PEDIDOS ===");

        Console.Write("Ingrese el monto del pedido: ");
        decimal montoPedido = Convert.ToDecimal(Console.ReadLine());

        Console.Write("Ingrese la ciudad destino: ");
        string ciudadDestino = Console.ReadLine().ToLower();

        Console.Write("Ingrese el tipo de cliente (nuevo / recurrente): ");               // Aqui debe ir el menu con las opciones, debe tener una lista y si el usuario se equivoca no debe tirar error
        string tipoCliente = Console.ReadLine().ToLower();

        Console.Write("Ingrese la cantidad de ítems: ");
        int cantidadItems = Convert.ToInt32(Console.ReadLine());

        // ===== VARIABLES =====
        string categoriaDespacho;
        decimal costoEnvio;
        string mensajeCliente;

        // 1°
        if (montoPedido >= 150000 && tipoCliente == "recurrente")
        {
            categoriaDespacho = "Envío Gratis";
            costoEnvio = 0;
        }
        // 2°
        else if (cantidadItems >= 5 || montoPedido >= 300000)
        {
            categoriaDespacho = "Envío Express";
            costoEnvio = 15000;
        }
        // 3°
        else
        {
            categoriaDespacho = "Envío Estándar";
            costoEnvio = 8000;
        }

        // 4°
        if (ciudadDestino == "exterior")
        {
            costoEnvio = costoEnvio + 20000;
        }

        // message
        mensajeCliente = "Su pedido fue clasificado como: " + categoriaDespacho +
                         ". El costo de envío es de $" + costoEnvio + ".";

        decimal totalPagar = montoPedido + costoEnvio;

        // end
        Console.WriteLine("\n=== RESULTADO DEL PEDIDO ===");
        Console.WriteLine(mensajeCliente);
        Console.WriteLine("El total a pagar (pedido + envío) es: $" + totalPagar);
        Console.WriteLine("Gracias por comprar con nosotros.");
    }
}
