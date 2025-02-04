/*
 * ===============================
 *      Hello, World! 👋
 * ===============================
 */

/**
 * ⭐️ Sobre mim:
 * Sou estudante de Análise e Desenvolvimento de Sistemas 🎓 na Faculdade Vincit.
 * Foco em desenvolvimento Back End com experiência em Java, PHP, e bancos de dados como MySQL, MongoDB e PostgreSQL.
 * Sempre em busca de aprender e compartilhar conhecimento 🧠. Meu objetivo é crescer profissionalmente e alcançar a estabilidade com meus projetos.
 * 
 * Além da programação, gosto de explorar ciências, atuar como voluntária em organizações como EngajaMundo e sou embaixadora no Papo Futuro.
 * Também gosto de ler livros clássicos 📚 e me aprofundar em temas de tecnologia.
 */

public class AboutMe {
    
    public static void main(String[] args) {
        String quote = "\"Em algum lugar, alguma coisa incrível está esperando para ser descoberta.\" - Carl Sagan";
        
        System.out.println(quote);  // Citação favorita de Carl Sagan
        
        // Espaço para adicionar GIFs animados (coloque o link do Giphy aqui)
        System.out.println("Aguardando GIF inspirador..."); 
    }
}

# ===================================
# 🎮 Pequeno jogo em Python
# ===================================
# Simples jogo de adivinhação de números

import random

def adivinhacao():
    numero_secreto = random.randint(1, 100)
    tentativas = 0
    print("Bem-vindo ao jogo de adivinhação! Tente adivinhar o número entre 1 e 100.")

    while True:
        tentativas += 1
        palpite = int(input("Digite seu palpite: "))

        if palpite < numero_secreto:
            print("O número é maior.")
        elif palpite > numero_secreto:
            print("O número é menor.")
        else:
            print(f"Parabéns! Você adivinhou o número {numero_secreto} em {tentativas} tentativas.")
            break

adivinhacao()

// Lista de habilidades técnicas
String[] hardSkills = {
    "Python", 
    "JavaScript", 
    "Kotlin", 
    "JSON", 
    "Selenium", 
    "Microsoft SQL Server", 
    "Arduino", 
    "Adobe XD", 
    "Java", 
    "PHP", 
    "AWS", 
    "Azure", 
    "Git", 
    "Flutter"
};

// Exibindo cada habilidade com seu respectivo badge
for (String skill : hardSkills) {
    System.out.println(skill + " badge");
}

// Redes sociais e contatos
String[] contacts = {
    "GitHub: https://github.com/Kell22-mkt", 
    "LinkedIn: https://www.linkedin.com/in/andreinaoliveira/", 
    "Email: kellyckarolin@gmail.com"
};

// Exibindo links de contato
for (String contact : contacts) {
    System.out.println(contact);
}



