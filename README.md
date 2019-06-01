# ChangeLog
Projeto MuServer 1.02i Pré Season 2

 | - Fix & Other's
 M:\ Drive
// # [GS And GSCS] - DestroyGIocp (Error - L10)
// # [GS And GSCS] - CGameServer Auth (0x00000 Memory Error)
// # [GS And GSCS] - ProtocolCore (Socket Serial Error)
// # [GS And GSCS] - Potion Bug
// # [GS And GSCS] - CGCheckMainRecv (CheckSum-Exe Error)
// # [GS And GSCS] - gObjCheckSerial0ItemList (Serial 0 Error)
// # [GS And GSCS] - Removida GgAuth.dll & GgSrvDll.dll
// # [GS And GSCS] - ReadCommonServerInfo (GameGuard Bypass)
// # [GS And GSCS] - GM Head Ballon
// # [GS And GSCS] - +28 Option
// # [GS And GSCS] - Disable Personal ID
// # [GS And GSCS] - Suporte 65535 Max Status
// # [GS And GSCS] - Potions 255
// # [GS And GSCS] - Instabilidade ao lotar o baú com pets
// # [GS And GSCS] - Dropar itens de pk's
// # [GS And GSCS] - Crash ao usar %s, %d em mensagens
// # [GS And GSCS] - Bug visual ao remover dark heaven
// # [GS And GSCS] - Invasão de dragões dourados
// # [GS And GSCS] - Atacar jogadores em party
// # [GS And GSCS] - Atacar gamemaster
// # [GS And GSCS] - Conexão com dataserver
// # [GS And GSCS] - Gamemaster locomover pelo M
// # [GS And GSCS] - Durabilidade dos itens iniciais
// # [GS And GSCS] - Durabilidade dos itens + 14 é + 15
// # [GS And GSCS] - Character sumir ao morrer
// # [GS And GSCS] - Consumo excessivo de memória ao recarregar a posição dos monstros
// # [GS And GSCS] - Adicional de itens até +28
// # [GS And GSCS] - Reparação de itens

// ==============================================================
// # | - Defaut Event's
// ==============================================================
// # [Emulador] # | - Devil Square.
// # [Emulador] # | - Blood Castle.
// # [Emulador] # | - Chaos Castle.
// # [Emulador] # | - Castle Siege.
// # [Emulador] # | - Kalima.
// # [Emulador] # | - Battle Soccer.
// # [Emulador] # | - Loren Deep.
// # [Emulador] # | - Golden Invasion.
// # [Emulador] # | - White Wizard.

// ==============================================================
// # | - Custom Event's
// ==============================================================
// # [Emulador] # | - Mata-Mata
// # [Emulador] # | - Pega-Pega
// # [Emulador] # | - Survivor
// # [Emulador] # | - Quiz
// # [Emulador] # | - Happy Hour
// # [Emulador] # | - Death Match
// # [Emulador] # | - Boss                       # Podendo cadastrar quantas invasões quiser.

// ==============================================================
// # | - Function
// ==============================================================
// # [Emulador] # | - Conexão com MSSQL.
// # [Emulador] # | - Anúncio de GM's Online.
// # [Emulador] # | - Mensagens de boas-Vindas.
// # [Emulador] # | - Selecionar personagem, servidores, sair em 1 segundo.
// # [Emulador] # | - Nova interface do gameserver.
// # [Emulador] # | - Novo ataque random do dark heaven.
// # [Emulador] # | - Adicionado reload de todas customs na interface do gameserver.
// # [Emulador] # | - Proteção contra trade hacker.
// # [Emulador] # | - Proteção contra dupe hacker.
// # [Emulador] # | - Proteção contra speed hacker.
// # [Emulador] # | - Nova GCReFillSend.
// # [Emulador] # | - Nova GCManaSend.

// ==============================================================
// # | - Server Config
// ==============================================================
// # [Emulador] # | - Pontos por level
// # [Emulador] # | - CheckSum
// # [Emulador] # | - Jogadores necessários para inicio do chaos castle
// # [Emulador] # | - Jogadores necessários para inicio de uma guild aliança
// # [Emulador] # | - Duração de itens dropados no chão
// # [Emulador] # | - Level para uso das skills do blade knight
// # [Emulador] # | - Configuração de fórmulas para buffs
// # [Emulador] # | - CalCharacter
// # [Emulador] # | - Configuração da taxa das potions
// # [Emulador] # | - Criação do dark lord
// # [Emulador] # | - Experiência free & vip's.
// # [Emulador] # | - DropRate free & vip's.
// # [Emulador] # | - Premiação do blood castle.
// # [Emulador] # | - Premiação do chaos castle.
// # [Emulador] # | - Porcentagem de mix da chaos machine.
// # [Emulador] # | - Porcentagem das jóias.
// # [Emulador] # | - Servidor vip ou iniciante.
// # [Emulador] # | - Zen Drop Rate

// ==============================================================
// # | - Comando Player
// ==============================================================
// # [Emulador] # | - /post			 # Mensagem global.
// # [Emulador] # | - /pkclear		         # Limpa o pk/hero do seu personagem.
// # [Emulador] # | - /reset                     # Aplica o reset em seu personagem.
// # [Emulador] # | - /mreset                    # Aplica o master reset em seu personagem.
// # [Emulador] # | - /readd                     # Redistribuir pontos.
// # [Emulador] # | - /for                       # Adiciona pontos em força.
// # [Emulador] # | - /agi                       # Adiciona pontos em agilidade.
// # [Emulador] # | - /vit                       # Adiciona pontos em vitalidade.
// # [Emulador] # | - /ene                       # Adiciona pontos em energia.
// # [Emulador] # | - /cmd                       # Adiciona pontos em carisma.
// # [Emulador] # | - /bau                       # Efetua a troca do baú.
// # [Emulador] # | - /zen                       # Adiciona zen ao personagem.
// # [Emulador] # | - /online                    # Mostra jogadores é GM's online.
// # [Emulador] # | - /ir                        # Participar de eventos.
// # [Emulador] # | - /bk                        # Muda a classe para Blade Knight.
// # [Emulador] # | - /sm                        # Muda a classe para Soul Master.
// # [Emulador] # | - /me                        # Muda a classe para Muse Elf.
// # [Emulador] # | - /mg                        # Muda a classe para Magic Gladiator.
// # [Emulador] # | - /dl                        # Muda a classe para Dark Lord.
// # [Emulador] # | - /irmatamata                # Participar do mata mata.
// # [Emulador] # | - /irpegapega                # Participar do pega pega.
// # [Emulador] # | - /irsurvivor                # Participar do survivor.

// ==============================================================
// # | - Comando GM/ADM
// ==============================================================
// # [Emulador] # | - /moveall		         # Move todos os jogadores.
// # [Emulador] # | - /disconnect                # Desconecta um jogador.
// # [Emulador] # | - /gmove              	 # Move um jogador.
// # [Emulador] # | - /trace       		 # Move você ate um jogador.
// # [Emulador] # | - /skin                      # Adiciona skin ao jogador.
// # [Emulador] # | - /premiar		         # Premia um jogador.
// # [Emulador] # | - /quiz		         # Cadastra uma resposta para o evento.
// # [Emulador] # | - /firework                  # Fogos de artifício.
// # [Emulador] # | - /matamata                  # Inicia um evento mata mata.
// # [Emulador] # | - /pegapega                  # Inicia um evento pega pega.
// # [Emulador] # | - /survivor                  # Inicia um evento survivor.
// # [Emulador] # | - /evento                    # Inicia um evento.
// # [Emulador] # | - /drop                      # Cria um item.
// # [Emulador] # | - !			         # Nome + mensagem para todos.

// ==============================================================
// # | - Correction Main
// ==============================================================
// # [Plugin] # | - Fonte.
// # [Plugin] # | - Acentuação.
// # [Plugin] # | - Texturas.
// # [Plugin] # | - Mover cursor ao abrir um npc.
// # [Plugin] # | - Interface visual (HP/MP/SD/AG)
// # [Plugin] # | - LevelUpPoint.
// # [Plugin] # | - Agilidade.
// # [Plugin] # | - GCReFillSend.
// # [Plugin] # | - GCManaSend.
// # [Plugin] # | - Experience Bar.
// # [Plugin] # | - Lag usando CTRL.
// # [Plugin] # | - Otimização no consumo de CPU.
// # [Plugin] # | - Skills do Siege
// # [Plugin] # | - NpcName.


// ==============================================================
// # | - Custom Main
// ==============================================================
// # [Plugin] # | - Auto click, F11 = Ativa, F11 = Desativa.
// # [Plugin] # | - Auto Ataque, F12 = Ativa, F12 = Desativa.
// # [Plugin] # | - Minimizer, F10 = Oculta, F10 = Restaura.
// # [Plugin] # | - Monster Heart Bar, F9 = Oculta, F9 = Desativa.
// # [Plugin] # | - Monster Fog, F8 = Oculta, F8 = Desativa.
// # [Plugin] # | - Novos itens liberados, Limite 255 por Categoria.
// # [Plugin] # | - MonsterHealthBar.
// # [Plugin] # | - Folder PrintScreen
// # [Plugin] # | - Folder MuError.log
// # [Plugin] # | - Folder MuError.Dump
// # [Plugin] # | - Decodificação MuError.log
// # [Plugin] # | - Glow
