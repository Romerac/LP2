# Ptestemetodos:

------------------------------------------------------------------------------------------------

#Ex1:

Criar uma aplicação Ptestemetodos e no form principal (renomear para frmPrincipal) e acrescentar 
um componente MenuStrip (categoria Menu & Toolbars)

• Menu - criado a partir do componente MenuStrip (categoria Menu & Toolbars) 

• Menu Item - criado como subitem do MenuStrip 

• Tecla de Atalho - Propriedade ShortCutKeys do MenuStrip 

• ShortCut(Atalho) - Na propriedade Text acrescentar o caracter “&” antes do caracter que deverá 
ser o atalho para a opção, junto com a tecla alt. No exemplo ALT + 2. 

• Menu Contexto – O Menu do contexto é criado a partir do componente ContextMenuStrip (categoria 
Menu & Toolbars), adicionam-se o itens. E no componente onde deve ser chamado esse menu na opção 
ContextMenuStrip, deverá ser setado o Menu de Contexto.

• Validação para evitar criação de mesmo formulário inúmeras vezes.

------------------------------------------------------------------------------------------------

# Ex2: 

Crie um Form com dois TextBoxs (txtPalavra1, txtPalavra2) e: 
• 1 botão para verificar se os dois textos são iguais (usando o método String.compare). 

• 1 botão para inserir o texto do primeiro TextBox no meio do segundo (usando Length e 
Substring). Colocar o resultado no segundo TextBox. 

• 1 botão para inserir 2 asteriscos no meio do texto do primeiro TextBox (usando Length e 
Insert) e colocar o resultado no segundo TextBox.

------------------------------------------------------------------------------------------------

# Ex3: 

Crie um form com dois TextBoxs (txtPalavra1 e txtPalavra2) e: 

• 1 botão que remova as ocorrências do Texto 1 no Texto 2 (usando replace), um botão que retorne 
o texto 1 de trás para frente (usando Array.reverse).

------------------------------------------------------------------------------------------------

# Ex4: 

Crie um form com um componente tipo RichText e: 
• 1 botão que mostre quantos caracteres numéricos existem dentro desse componente (usando 
isNumber e while), 

• 1 botão que localize o primeiro caracter branco e mostre a sua posição (usando isWhiteSpace 
e for) 

• 1 botão que mostre quantos caracteres alfabéticos existem dentro desse componente (usando 
isLetter e foreach).

------------------------------------------------------------------------------------------------

# Ex5: 

Crie um form com 2 TextBoxs (txtNumero1, txtNumero2) e: 
• 1 botão que realize um sorteio entre o primeiro e o segundo número. (usando random). 
• Validar se é número e se numero1 é menor que numero2.

------------------------------------------------------------------------------------------------
------------------------------------------------------------------------------------------------

# Ptestemetodos:
#Ex1:
Create an application named Ptestemetodos and, in the main form (rename it to frmPrincipal), 
add a MenuStrip component (from the "Menu & Toolbars" category).

• Menu – created using the MenuStrip component (Menu & Toolbars category).

• Menu Item – created as a submenu of the MenuStrip.

• Shortcut Key – use the ShortCutKeys property of the MenuStrip.

• Shortcut (Hotkey) – in the Text property, add the character “&” before the character that 
should be used as the shortcut key, together with the Alt key. Example: ALT + 2.

• Context Menu – the context menu is created using the ContextMenuStrip component (Menu & 
Toolbars category). Add the items, and in the component where the context menu should appear, 
set the ContextMenuStrip property to the corresponding menu.

• Implement validation to prevent multiple instances of the same form from being created.

------------------------------------------------------------------------------------------------

#Ex2:
Create a form with two TextBoxes (txtPalavra1, txtPalavra2) and:

• A button to check if the two texts are equal (using the String.Compare method).

• A button to insert the text from the first TextBox into the middle of the second one (using 
Length and Substring). Show the result in the second TextBox.

• A button to insert two asterisks ** in the middle of the text from the first TextBox (using 
Length and Insert) and show the result in the second TextBox.

------------------------------------------------------------------------------------------------

#Ex3:
Create a form with two TextBoxes (txtPalavra1 and txtPalavra2) and:

• A button that removes occurrences of TextBox1's text from TextBox2 (using Replace).

• A button that returns the text from TextBox1 reversed (using Array.Reverse).

------------------------------------------------------------------------------------------------

#Ex4:
Create a form with a RichTextBox component and:

• A button that shows how many numeric characters exist in the component (using Char.IsNumber 
and while).

• A button that finds the first whitespace character and shows its position (using 
Char.IsWhiteSpace and for).

• A button that shows how many alphabetic characters exist in the component (using 
Char.IsLetter and foreach).

------------------------------------------------------------------------------------------------

#Ex5:
Create a form with two TextBoxes (txtNumero1, txtNumero2) and:

• A button that performs a random draw between the first and second numbers (using Random).
• Validate if the inputs are numbers and if numero1 is less than numero2.

