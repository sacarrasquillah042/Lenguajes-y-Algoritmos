En Python:

a=input("cuantas veces queres tener un 'hola mundo'? ") a=int(a)

for i in range(a): print("Hola mundo")

En Julia:

println("Ingresa el número de veces que quieres imprimir 'hola mundo': ") n = parse(Int, readline())

for i in 1:n println("hola mundo") end

En Fortran:

program hola_mundo implicit none integer :: n, i

write(,) 'Ingresa el número de veces que quieres imprimir "hola mundo": ' read(,) n

do i = 1, n write(,) 'hola mundo' end do

end program hola_mundo

En Java:

import java.util.Scanner;

public class HolaMundo { public static void main(String[] args) { Scanner scanner = new Scanner(System.in); int n; System.out.print("Ingresa el número de veces que quieres imprimir 'hola mundo': "); n = scanner.nextInt(); for (int i = 1; i <= n; i++) { System.out.println("hola mundo"); } } }

En C++:

#include using namespace std;

int main() { int n; cout << "Ingresa el número de veces que quieres imprimir 'hola mundo': "; cin >> n; for (int i = 1; i <= n; i++) { cout << "hola mundo" << endl; } return 0; }