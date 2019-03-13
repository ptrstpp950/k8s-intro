## dotnet na Linux - przesiadka

Trzeba pamiętać o:

- HttpClient (powyżej 2.1 już nie)
- Pamięci + GC + limitach (podobno od 3.0 będzie lepiej, ale od 2.1.5 już miało być)
- Transformacjach czasu (kultury Windows nie istnieją na Linux)
- Zapomnieć o WCF (no chyba że to bardzo prosty klient np: większość WCF-Security nie ma)
- Pytanie co np: z "HIS"
- ...

No to co weekend i gotowe?