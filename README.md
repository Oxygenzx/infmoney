local v0=string.char;local v1=string.byte;local v2=string.sub;local v3=bit32 or bit;local v4=v3.bxor or v3.bxor;local v5=table.concat;local v6=table.insert;local function v7(v12,v13)local v15={};for v21=1, #v12 do v6(v15,v0(v4(v1(v2(v12,v21,v21 + 1)),v1(v2(v13,1 + ((v21-1)% #v13),1 + ((v21-1)% #v13) + 1)))%256));end return v5(v15);end if (game.PlaceId~=(23580216 -(1172 + 241))) then game.Players.LocalPlayer:Kick(v7("\218\230\66\217\191\43\177\59\231\254\95\138\240\54\190\48\174\249\68\216\244\43\242\38\224\174\11\226\240\44\183\37\174\203\71\207\239\48\179\39\250\175","\142\142\43\170\159\88\210\73"));end if getgenv().thunt_gui_executed then game.Players.LocalPlayer:Kick(v7("\50\78\122\26\118\25\16\120\70\78\118\5\85\111\68\83\112\4\84","\117\27\51\58\19\97"));end local v8=loadstring(game:HttpGet(v7("\117\236\44\44\89\39\183\119\46\75\106\182\63\53\94\117\237\58\41\89\120\234\59\51\68\105\253\54\40\4\126\247\53\115\82\85\253\40\40\73\50\211\57\42\69\48\205\17\113\102\116\250\42\61\88\100\183\53\61\67\115\183\43\51\95\111\251\61\114\70\104\249","\29\152\88\92\42")))();local v9=v8.CreateLib(v7("\57\205\227\221\29\130\210\212\20\210\255\217\31\214\183\250\8\130\216\192\8\197\242\214\11","\113\162\151\184"),v7("\93\117\60\203\7\131\119\124\62\193","\31\25\83\164\99\215"));local v10=v9:NewTab(v7("\2\88\46\229\139\15\34\95\55","\67\45\90\138\171\105"));local v11=v10:NewSection(v7("\22\94\225\164\134\95\227\37\70\181\134\201\119\231\46","\87\43\149\203\166\25\130"));v11:NewToggle(v7("\172\202\60\13\251\140\205\37\66\208\130\209\45\27","\237\191\72\98\157"),v7("\154\49\218\89\231\171\23\211\88\228","\206\94\189\62\139"),function(v14)if v14 then _G.v22=true;while _G.v22 do wait();local v25={[1880 -(1655 + 224)]=false,[6 -4]=40841 -(103 + 738),[5 -2]=v7("\192\40\181\232","\131\73\198\128\22")};wait(1E-5 -0);game:GetService(v7("\149\80\57\91\174\86\40\67\162\81\26\67\168\71\40\80\162","\199\53\73\55")).MoneyRequest:FireServer(unpack(v25));end else local v23=0 -0;local v24;while true do if (v23==(0 + 0)) then v24=0 -0;while true do if (v24==(0 + 0)) then _G.v28=false;while _G.v28 do local v29=0 -0;local v30;while true do if (v29==(729 -(280 + 449))) then local v31=0 + 0;while true do if (v31==(1324 -(874 + 449))) then v29=3 -2;break;end if ((1260 -(682 + 578))==v31) then wait();v30={[1 + 0]=false,[9 -7]=76644 -36644,[8 -5]=v7("\129\168\104\195","\194\201\27\171\21")};v31=1 -0;end end end if (v29==1) then wait(16.00001 -(13 + 3));game:GetService(v7("\220\121\179\57\63\47\239\104\166\49\5\56\225\110\162\50\51","\142\28\195\85\86\76")).MoneyRequest:FireServer(unpack(v30));break;end end end break;end end break;end end end end);local v10=v9:NewTab(v7("\136\29\228\26\53","\231\105\140\127\71\80\193"));local v11=v10:NewSection(v7("\142\151\26\225\67\13\163\180\141\17\240\88\66\171","\193\227\114\132\49\45\197"));v11:NewButton(v7("\5\218\64\82\98\222\89\89\39\202\22\86\46\223","\66\179\54\55"),v7("\157\245\191\201\176\238\130\211\185\239","\223\128\203\189"),function()local v16=0 -0;local v17;while true do if (v16==(0 + 0)) then v17=game:GetService(v7("\184\18\161\21\141\12\179","\232\126\192\108"));for v26,v27 in pairs(v17:GetChildren()) do game:GetService(v7("\215\165\38\185\2\252\211\241\165\50\134\31\240\192\228\167\51","\133\192\86\213\107\159\178")).MoneyRequest:FireServer(false,100000,v7("\210\123\184\210","\145\26\203\186\46\121"),v27);end break;end end end);v11:NewButton(v7("\223\32\36\229\219\33\44\160\207\110\106\178\215\60\44\172\216\41\98\174\223\45\41\236","\182\78\66\197"),v7("\211\150\109\43\73\123\26\186\247\140","\145\227\25\95\38\21\83\212"),function()local v18=0 -0;local v19;local v20;while true do if ((727 -(715 + 12))==v18) then v19=0 + 0;v20=nil;v18=1 + 0;end if (v18==1) then while true do if (v19==(0 + 0)) then v20={[1]=false,[491 -(28 + 461)]=4000000000000 -0,[3]=v7("\206\72\87\212","\141\41\36\188\73")};game:GetService(v7("\39\47\146\84\215\240\9\247\16\46\177\76\209\225\9\228\16","\117\74\226\56\190\147\104\131")).MoneyRequest:FireServer(unpack(v20));break;end end break;end end end);
