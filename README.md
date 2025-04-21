<?php
// Inclui a classe Paciente
require_once 'Paciente.php';

// Criação de um objeto Paciente
$paciente1 = new Paciente();

// Definindo os dados do paciente usando os Setters
$paciente1->setNome("João da Silva");
$paciente1->setRg("12345678-9");
$paciente1->setCpf("111.222.333-44");
$paciente1->setEndereco("Rua das Flores, 123 - Bairro Jardim");
$paciente1->setProfissao("Professor");

// Exibindo os dados do paciente usando os Getters
echo "<h2>Dados do Paciente</h2>";
echo "Nome: " . $paciente1->getNome() . "<br>";
echo "RG: " . $paciente1->getRg() . "<br>";
echo "CPF: " . $paciente1->getCpf() . "<br>";
echo "Endereço: " . $paciente1->getEndereco() . "<br>";
echo "Profissão: " . $paciente1->getProfissao() . "<br>";
?>





