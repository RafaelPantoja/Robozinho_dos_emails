# Robozinho_dos_emails
Automação de envio de emails

# Rafael Tavares Pantoja
# Analista de Software Júnior

import  pyautogui 

pyautogui.PAUSE = 4

# Abrir a ferramenta
pyautogui.press("win")
pyautogui.write("google Chrome")
pyautogui.press("backspace")
pyautogui.press("enter")
# escolhee a conta para logar
pyautogui.click(x=618, y=465)
# vai até o url e digita o endereço do email
pyautogui.click(x=629, y=70)
pyautogui.write("https://outlook.live.com/owa/")
pyautogui.press("enter")
# faz os processos de entrada
pyautogui.click(x=1514, y=170)
pyautogui.click(x=1159, y=670)
pyautogui.click(x=1159, y=670)
pyautogui.click(x=1102, y=690)
pyautogui.click(x=1107, y=742)
# escrever um email de teste para o meu email
pyautogui.click(x=232, y=255)
pyautogui.click(x=1115, y=364) #clica novo email
pyautogui.click(x=1083, y=331)
pyautogui.write("rafael_hss_studio@hotmail.com") # escreve o email
pyautogui.click(x=816, y=451)
pyautogui.write("Teste de email automatizado BB'S")
pyautogui.click(x=822, y=855) #clica em enviar
pyautogui.click(x=942, y=646) #confirmar envio de email sem assunto


