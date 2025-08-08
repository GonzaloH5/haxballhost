// ------------------------------------------------
// Bot creado by Cherry | Youtube: Cherry  / Discord: cherry_youtube
// ------------------------------------------------

var roomName = "Servidor Oficial de la Liga";
var roomPassword = null;
var maxPlayers = 22;
var roomPublic = false;
var token = "thr1.AAAAAGiWbD1bcIJ87mmGyw.5_SazWjVxkE"; // <-- Pega tu token aquí
var gameTime = 10;
var adminCode = "g0nz4l0cc"; // !admin contraseña


var room = HBInit({
	roomName: roomName,
	password: roomPassword,
	maxPlayers: maxPlayers,
	public: roomPublic,
	geo: null,
	noPlayer: false, // Cambia esto a false
	token: token
});

/*-------------------------------- Estadios ---------------------------------*/

function getRealSoccerMap() {
	var realSoccerMap = `{"name":"Real Soccer Revolution","width":1300,"height":670,"spawnDistance":560,"bg":{"type":"grass","width":1150,"height":600,"kickOffRadius":180,"cornerRadius":0,"color":"` + mapBGColor + `"},"playerPhysics":{"bCoef":0.3,"invMass":0.5,"damping":0.96,"acceleration":0.12,"kickingAcceleration":0.07,"kickingDamping":0.96,"kickStrength":5.65},"ballPhysics":{"radius":9,"bCoef":0.5,"invMass":1.05,"damping":0.99,"color":"FFFFFF","cMask":["all"],"cGroup":["ball"]},"vertexes":[{"x":0,"y":675,"trait":"kickOffBarrier"},{"x":0,"y":180,"trait":"kickOffBarrier"},{"x":0,"y":-180,"trait":"kickOffBarrier"},{"x":0,"y":-675,"trait":"kickOffBarrier"},{"x":1150,"y":320,"trait":"line"},{"x":840,"y":320,"trait":"line"},{"x":1150,"y":-320,"trait":"line"},{"x":840,"y":-320,"trait":"line"},{"x":1150,"y":180,"trait":"line"},{"x":1030,"y":180,"trait":"line"},{"x":1150,"y":-180,"trait":"line"},{"x":1030,"y":-180,"trait":"line"},{"x":840,"y":-130,"trait":"line","curve":-130},{"x":840,"y":130,"trait":"line","curve":-130},{"x":-1150,"y":-320,"trait":"line"},{"x":-840,"y":-320,"trait":"line"},{"x":-1150,"y":320,"trait":"line"},{"x":-840,"y":320,"trait":"line"},{"x":-1150,"y":-175,"trait":"line"},{"x":-1030,"y":-175,"trait":"line"},{"x":-1150,"y":175,"trait":"line"},{"x":-1030,"y":175,"trait":"line"},{"x":-840,"y":130,"trait":"line","curve":-130},{"x":-840,"y":-130,"trait":"line","curve":-130},{"x":935,"y":3,"trait":"line"},{"x":935,"y":-3,"trait":"line"},{"x":-935,"y":3,"trait":"line"},{"x":-935,"y":-3,"trait":"line"},{"x":-1150,"y":570,"bCoef":-2.65,"cMask":["ball"],"cGroup":["c0"],"trait":"line"},{"x":-1120,"y":600,"bCoef":-2.65,"cMask":["ball"],"cGroup":["c0"],"trait":"line"},{"x":-1120,"y":-600,"bCoef":-2.65,"cMask":["ball"],"cGroup":["c0"],"trait":"line"},{"x":-1150,"y":-570,"bCoef":-2.65,"cMask":["ball"],"cGroup":["c0"],"trait":"line"},{"x":1120,"y":600,"bCoef":-2.65,"cMask":["ball"],"cGroup":["c0"],"trait":"line"},{"x":1150,"y":570,"bCoef":-2.65,"cMask":["ball"],"cGroup":["c0"],"trait":"line"},{"x":1150,"y":-570,"bCoef":-2.65,"cMask":["ball"],"cGroup":["c0"],"trait":"line"},{"x":1120,"y":-600,"bCoef":-2.65,"cMask":["ball"],"cGroup":["c0"],"trait":"line"},{"x":0,"y":180,"bCoef":0.1,"cMask":["red","blue"],"cGroup":["blueKO"],"trait":"kickOffBarrier","curve":-180},{"x":0,"y":-180,"bCoef":0.1,"cMask":["red","blue"],"cGroup":["redKO"],"trait":"kickOffBarrier","curve":180},{"x":0,"y":180,"bCoef":0.1,"cMask":["red","blue"],"cGroup":["redKO"],"trait":"kickOffBarrier","curve":180},{"x":-1030,"y":-40,"bCoef":-5.7,"cMask":["ball"],"cGroup":["c0"],"trait":"line","curve":70,"color":"576C46","vis":false},{"x":-1030,"y":40,"bCoef":-5.7,"cMask":["ball"],"cGroup":["c0"],"trait":"line","curve":70,"color":"576C46","vis":false},{"x":1030,"y":-40,"bCoef":-5.7,"cMask":["ball"],"cGroup":["c0"],"trait":"line","curve":-70,"color":"576C46","vis":false},{"x":1030,"y":40,"bCoef":-5.7,"cMask":["ball"],"cGroup":["c0"],"trait":"line","curve":-70,"color":"576C46","vis":false},{"x":1030,"y":-40,"trait":"line","color":"576C46"},{"x":1030,"y":40,"trait":"line","color":"576C46"},{"x":-1030,"y":-40,"trait":"line","color":"576C46"},{"x":-1030,"y":40,"trait":"line","color":"576C46"},{"x":0,"y":3,"trait":"line"},{"x":0,"y":-3,"trait":"line"},{"x":-1157,"y":605,"bCoef":0,"cMask":["ball"],"trait":"ballArea"},{"x":-1157,"y":655,"bCoef":0,"cMask":["ball"],"trait":"ballArea"},{"x":-1157,"y":-655,"bCoef":0,"cMask":["ball"],"trait":"ballArea"},{"x":-1157,"y":-605,"bCoef":0,"cMask":["ball"],"trait":"ballArea"},{"x":1157,"y":605,"bCoef":0,"cMask":["ball"],"trait":"ballArea"},{"x":1157,"y":655,"bCoef":0,"cMask":["ball"],"trait":"ballArea"},{"x":1157,"y":-655,"bCoef":0,"cMask":["ball"],"trait":"ballArea"},{"x":1157,"y":-605,"bCoef":0,"cMask":["ball"],"trait":"ballArea"},{"x":-1300,"y":-485,"bCoef":0,"cMask":["c1"],"cGroup":["red","blue"],"color":"ec644b","vis":false},{"x":1300,"y":-485,"bCoef":0,"cMask":["c1"],"cGroup":["red","blue"],"color":"ec644b","vis":false},{"x":-1300,"y":485,"bCoef":0,"cMask":["c1"],"cGroup":["red","blue"],"color":"ec644b","vis":false},{"x":1300,"y":485,"bCoef":0,"cMask":["c1"],"cGroup":["red","blue"],"color":"ec644b","vis":false},{"x":-1295,"y":-320,"cMask":["c0"],"cGroup":["red","blue"]},{"x":-840,"y":-320,"cMask":["c0"],"cGroup":["red","blue"]},{"x":-840,"y":320,"cMask":["c0"],"cGroup":["red","blue"]},{"x":-1295,"y":320,"cMask":["c0"],"cGroup":["red","blue"]},{"x":1295,"y":-320,"cMask":["c0"],"cGroup":["red","blue"]},{"x":840,"y":-320,"cMask":["c0"],"cGroup":["red","blue"]},{"x":840,"y":320,"cMask":["c0"],"cGroup":["red","blue"]},{"x":1295,"y":320,"cMask":["c0"],"cGroup":["red","blue"]},{"x":-1150,"y":-124,"bCoef":0,"cMask":["ball","red","blue"]},{"x":-1210,"y":-124,"bCoef":0,"cMask":["ball"],"bias":0,"curve":5},{"x":-1150,"y":124,"bCoef":0,"cMask":["ball","red","blue"]},{"x":-1210,"y":124,"bCoef":0,"cMask":["ball"],"bias":0,"curve":5},{"x":-1250,"y":-158,"bCoef":0,"cMask":["ball"]},{"x":-1250,"y":158,"bCoef":0,"cMask":["ball"]},{"x":1150,"y":124,"bCoef":0,"cMask":["ball","red","blue"]},{"x":1210,"y":124,"bCoef":0,"cMask":["ball"],"curve":-5},{"x":1150,"y":-124,"bCoef":0,"cMask":["ball","red","blue"]},{"x":1210,"y":-124,"bCoef":0,"cMask":["ball"],"curve":-5},{"x":1250,"y":-158,"bCoef":0,"cMask":["ball"]},{"x":1250,"y":158,"bCoef":0,"cMask":["ball"]}],"segments":[{"v0":0,"v1":1,"trait":"kickOffBarrier"},{"v0":2,"v1":3,"trait":"kickOffBarrier"},{"v0":4,"v1":5,"trait":"line","y":320},{"v0":5,"v1":7,"trait":"line","x":840},{"v0":6,"v1":7,"trait":"line","y":-320},{"v0":8,"v1":9,"trait":"line","y":180},{"v0":9,"v1":11,"trait":"line","x":1030},{"v0":10,"v1":11,"trait":"line","y":-180},{"v0":12,"v1":13,"curve":-130,"trait":"line","x":840},{"v0":14,"v1":15,"trait":"line","y":-320},{"v0":15,"v1":17,"trait":"line","x":-840},{"v0":16,"v1":17,"trait":"line","y":320},{"v0":18,"v1":19,"trait":"line","y":-175},{"v0":19,"v1":21,"trait":"line","x":-1030},{"v0":20,"v1":21,"trait":"line","y":175},{"v0":22,"v1":23,"curve":-130,"trait":"line","x":-840},{"v0":24,"v1":25,"curve":-180,"trait":"line","x":935},{"v0":26,"v1":27,"curve":-180,"trait":"line","x":-935},{"v0":24,"v1":25,"curve":180,"trait":"line","x":935},{"v0":26,"v1":27,"curve":180,"trait":"line","x":-935},{"v0":24,"v1":25,"curve":90,"trait":"line","x":935},{"v0":26,"v1":27,"curve":90,"trait":"line","x":-935},{"v0":24,"v1":25,"curve":-90,"trait":"line","x":935},{"v0":26,"v1":27,"curve":-90,"trait":"line","x":-935},{"v0":24,"v1":25,"trait":"line","x":935},{"v0":26,"v1":27,"trait":"line","x":-935},{"v0":28,"v1":29,"curve":90,"bCoef":-2.65,"cMask":["ball"],"cGroup":["c0"],"trait":"line"},{"v0":30,"v1":31,"curve":90,"bCoef":-2.65,"cMask":["ball"],"cGroup":["c0"],"trait":"line"},{"v0":32,"v1":33,"curve":90,"bCoef":-2.65,"cMask":["ball"],"cGroup":["c0"],"trait":"line"},{"v0":34,"v1":35,"curve":90,"bCoef":-2.65,"cMask":["ball"],"cGroup":["c0"],"trait":"line"},{"v0":37,"v1":36,"curve":-180,"vis":false,"bCoef":0.1,"cGroup":["blueKO"],"trait":"kickOffBarrier"},{"v0":39,"v1":40,"curve":70,"vis":false,"color":"576C46","bCoef":-5.7,"cMask":["ball"],"cGroup":["c0"],"trait":"line","x":-1030},{"v0":41,"v1":42,"curve":-70,"vis":false,"color":"576C46","bCoef":-5.7,"cMask":["ball"],"cGroup":["c0"],"trait":"line","x":1030},{"v0":37,"v1":38,"curve":180,"vis":false,"bCoef":0.1,"cMask":["red","blue"],"cGroup":["redKO"],"trait":"kickOffBarrier"},{"v0":43,"v1":44,"vis":true,"color":"576C46","trait":"line","x":1030},{"v0":45,"v1":46,"vis":true,"color":"576C46","trait":"line","x":-1030},{"v0":47,"v1":48,"curve":-180,"trait":"line","x":-935},{"v0":47,"v1":48,"curve":180,"trait":"line","x":-935},{"v0":47,"v1":48,"curve":90,"trait":"line","x":-935},{"v0":47,"v1":48,"curve":-90,"trait":"line","x":-935},{"v0":47,"v1":48,"trait":"line","x":-935},{"v0":49,"v1":50,"color":"FFFF00","bCoef":0,"cMask":["ball"],"trait":"ballArea","x":-1157},{"v0":51,"v1":52,"color":"FFFF00","bCoef":0,"cMask":["ball"],"trait":"ballArea","x":-1157},{"v0":53,"v1":54,"color":"FFFF00","bCoef":0,"cMask":["ball"],"trait":"ballArea","x":1157},{"v0":55,"v1":56,"color":"FFFF00","bCoef":0,"cMask":["ball"],"trait":"ballArea","x":1157},{"v0":57,"v1":58,"vis":false,"color":"ec644b","bCoef":0,"cMask":["c1"],"cGroup":["red","blue"],"y":-485},{"v0":59,"v1":60,"vis":false,"color":"ec644b","bCoef":0,"cMask":["c1"],"cGroup":["red","blue"],"y":485},{"v0":61,"v1":62,"vis":false,"color":"ec644b","cMask":["c0"],"cGroup":["red","blue"]},{"v0":62,"v1":63,"vis":false,"color":"ec644b","cMask":["c0"],"cGroup":["red","blue"]},{"v0":63,"v1":64,"vis":false,"color":"ec644b","cMask":["c0"],"cGroup":["red","blue"]},{"v0":65,"v1":66,"vis":false,"cMask":["c0"],"cGroup":["red","blue"]},{"v0":66,"v1":67,"vis":false,"cMask":["c0"],"cGroup":["red","blue"]},{"v0":67,"v1":68,"vis":false,"cMask":["c0"],"cGroup":["red","blue"]},{"v0":69,"v1":70,"color":"FFFFFF","bCoef":0,"cMask":["ball","red","blue"],"y":-124},{"v0":71,"v1":72,"color":"FFFFFF","bCoef":0,"cMask":["ball","red","blue"],"y":124},{"v0":72,"v1":70,"curve":5,"color":"FFFFFF","bCoef":0,"cMask":["ball","red","blue"],"bias":0},{"v0":70,"v1":73,"color":"FFFFFF","bCoef":0,"cMask":["ball"]},{"v0":72,"v1":74,"color":"FFFFFF","bCoef":0,"cMask":["ball"]},{"v0":75,"v1":76,"color":"FFFFFF","bCoef":0,"cMask":["ball","red","blue"],"y":124},{"v0":77,"v1":78,"color":"FFFFFF","bCoef":0,"cMask":["ball","red","blue"],"y":-124},{"v0":76,"v1":78,"curve":-5,"color":"FFFFFF","bCoef":0,"cMask":["ball","red","blue"]},{"v0":78,"v1":79,"color":"FFFFFF","bCoef":0,"cMask":["ball"]},{"v0":76,"v1":80,"color":"FFFFFF","bCoef":0,"cMask":["ball"]}],"goals":[{"p0":[-1162.45,124],"p1":[-1162.45,-124],"team":"red"},{"p0":[1162.45,124],"p1":[1162.45,-124],"team":"blue","radius":0,"invMass":1}],"discs":[{"radius":0,"invMass":0,"pos":[-1311,-19],"color":"ffffffff","bCoef":0,"cMask":["red"],"cGroup":["ball"]},{"radius":0,"invMass":0,"pos":[-1310,29],"color":"ffffffff","bCoef":0,"cMask":["blue"],"cGroup":["ball"]},{"radius":0,"invMass":0,"pos":[-1308,62],"color":"ffffffff","bCoef":0,"cMask":["red","blue"],"cGroup":["ball"]},{"radius":2.7,"pos":[-1150,600],"cGroup":["ball"],"trait":"cornerflag"},{"radius":2.7,"pos":[1150,-600],"cGroup":["ball"],"trait":"cornerflag"},{"radius":2.7,"pos":[1150,600],"cGroup":["ball"],"trait":"cornerflag"},{"radius":5,"invMass":0,"pos":[-1150,-124],"bCoef":0.5,"trait":"goalPost"},{"radius":5,"invMass":0,"pos":[-1150,124],"bCoef":0.5,"trait":"goalPost"},{"radius":2,"invMass":0,"pos":[-1250,-158],"color":"000000","bCoef":1,"trait":"goalPost"},{"radius":2,"invMass":0,"pos":[-1250,158],"color":"000000","bCoef":1,"trait":"goalPost"},{"radius":5,"invMass":0,"pos":[1150,-124],"bCoef":0.5,"trait":"goalPost"},{"radius":5,"invMass":0,"pos":[1150,124],"bCoef":0.5,"trait":"goalPost"},{"radius":2,"invMass":0,"pos":[1250,-158],"color":"000000","bCoef":1,"trait":"goalPost"},{"radius":2,"invMass":0,"pos":[1250,158],"color":"000000","bCoef":1,"trait":"goalPost"},{"radius":2.7,"pos":[-1150,-600],"cGroup":["ball"],"trait":"cornerflag"},{"radius":0,"pos":[-1149,-485],"cMask":["none"]},{"radius":0,"pos":[1149,-485],"cMask":["none"]},{"radius":0,"pos":[-1149,-485],"cMask":["none"]},{"radius":0,"pos":[1149,-485],"cMask":["none"]},{"radius":0,"pos":[-1149,485],"cMask":["none"]},{"radius":0,"pos":[1149,485],"cMask":["none"]},{"radius":0,"pos":[-1149,485],"cMask":["none"]},{"radius":0,"pos":[1149,485],"cMask":["none"]}],"planes":[{"normal":[0,1],"dist":-627,"bCoef":0,"cGroup":["ball"],"trait":"ballArea","_data":{"extremes":{"normal":[0,1],"dist":-627,"canvas_rect":[-1311,-675,1300,675],"a":[-1311,-627],"b":[1300,-627]}}},{"normal":[0,-1],"dist":-627,"bCoef":0,"cGroup":["ball"],"trait":"ballArea","_data":{"extremes":{"normal":[0,-1],"dist":-627,"canvas_rect":[-1311,-675,1300,675],"a":[-1311,627],"b":[1300,627]},"mirror":{}}},{"normal":[0,1],"dist":-670,"bCoef":0,"_data":{"extremes":{"normal":[0,1],"dist":-670,"canvas_rect":[-1311,-675,1300,675],"a":[-1311,-670],"b":[1300,-670]},"mirror":{}}},{"normal":[0,-1],"dist":-670,"bCoef":0,"_data":{"extremes":{"normal":[0,-1],"dist":-670,"canvas_rect":[-1311,-675,1300,675],"a":[-1311,670],"b":[1300,670]},"mirror":{}}},{"normal":[1,0],"dist":-1300,"bCoef":0,"_data":{"extremes":{"normal":[1,0],"dist":-1300,"canvas_rect":[-1311,-675,1300,675],"a":[-1300,-675],"b":[-1300,675]}}},{"normal":[-1,0],"dist":-1300,"bCoef":0.1,"_data":{"extremes":{"normal":[-1,0],"dist":-1300,"canvas_rect":[-1311,-675,1300,675],"a":[1300,-675],"b":[1300,675]}}},{"normal":[1,0],"dist":-1230,"bCoef":0,"cMask":["ball"],"cGroup":["ball"],"_data":{"extremes":{"normal":[1,0],"dist":-1230,"canvas_rect":[-1311,-675,1300,675],"a":[-1230,-675],"b":[-1230,675]}}},{"normal":[-1,0],"dist":-1230,"bCoef":0,"cMask":["ball"],"cGroup":["ball"],"_data":{"extremes":{"normal":[-1,0],"dist":-1230,"canvas_rect":[-1311,-675,1300,675],"a":[1230,-675],"b":[1230,675]}}}],"traits":{"ballArea":{"vis":false,"bCoef":0,"cMask":["ball"],"cGroup":["ball"]},"goalPost":{"radius":5,"invMass":0,"bCoef":1,"cGroup":["ball"]},"rightNet":{"radius":0,"invMass":1,"bCoef":0,"cGroup":["ball","c3"]},"leftNet":{"radius":0,"invMass":1,"bCoef":0,"cGroup":["ball","c2"]},"stanchion":{"radius":3,"invMass":0,"bCoef":3,"cMask":["none"]},"cornerflag":{"radius":3,"invMass":0,"bCoef":0.2,"color":"FFFF00","cMask":["ball"]},"reargoalNetleft":{"vis":true,"bCoef":0.1,"cMask":["ball","red","blue"],"curve":10,"color":"C7E6BD"},"reargoalNetright":{"vis":true,"bCoef":0.1,"cMask":["ball","red","blue"],"curve":-10,"color":"C7E6BD"},"sidegoalNet":{"vis":true,"bCoef":1,"cMask":["ball","red","blue"],"color":"C7E6BD"},"kickOffBarrier":{"vis":false,"bCoef":0.1,"cGroup":["redKO","blueKO"],"cMask":["red","blue"]},"line":{"vis":true,"cMask":[],"color":"C7E6BD"}},"joints":[{"d0":16,"d1":17,"strength":"rigid","color":"ec7458","length":null},{"d0":18,"d1":19,"strength":"rigid","color":"48bef9","length":null},{"d0":20,"d1":21,"strength":"rigid","color":"ec7458","length":null},{"d0":22,"d1":23,"strength":"rigid","color":"48bef9","length":null}],"redSpawnPoints":[],"blueSpawnPoints":[],"canBeStored":false}`;

	return realSoccerMap;
}

/*------------------------------ FIN ESTADIOS ----------------------------*/


var throwTimeOut = 420;
var gkTimeOut = 600;
var ckTimeOut = 600;
var throwinDistance = 270;
var mapBGColor = "86A578";
var map = "RSR";
let discordLink = "https://discord.gg/CHjaCjA2"
var roomLink = "";
let firmas = new Set()

// -------------------------------------------------
// Webhooks
// -------------------------------------------------

let replayWebHook = "https://discord.com/api/webhooks/1187900457176272958/HfHXRLycUDpl03gLfUIBnIzXr2upJtH0oS4VfvN_6O4QSt-5Moy6BdgV9OCOBWtjinBh"
let firmasWebHook = "https://discord.com/api/webhooks/1187900640190541914/nuPx3KAq-G58mixEAnsfhYnwABAAjoiYowg8laBSYjFjjJpv1ladZOowxdqUvvsClLUi"

// -------------------------------------------------
// Clases
// -------------------------------------------------
class Game {
	constructor() {
		this.time = 0;
		this.paused = false;
		this.ballRadius;
		this.rsTouchTeam = 0;
		this.rsActive = true;
		this.rsReady = false;
		this.rsCorner = false;
		this.rsGoalKick = false;
		this.rsSwingTimer = 1000;
		this.rsTimer;
		this.ballOutPositionX;
		this.ballOutPositionY;
		this.throwInPosY;
		this.outStatus = "";
		this.warningCount = 0;
		this.bringThrowBack = false;
		this.extraTime = false;
		this.extraTimeCount = 0;
		this.extraTimeEnd;
		this.extraTimeAnnounced = false;
		this.lastPlayAnnounced = false;
		this.boosterState;
		this.throwinKicked = false;
		this.pushedOut;
		this.lastKickerId;
		this.lastKickerName;
		this.lastKickerTeam;
		this.secondLastKickerId;
		this.secondLastKickerName;
		this.secondLastKickerTeam;
		this.redScore = 0;
		this.blueScore = 0;
	}

	updateLastKicker(id, name, team) {
		this.secondLastKickerId = this.lastKickerId;
		this.secondLastKickerName = this.lastKickerName;
		this.secondLastKickerTeam = this.lastKickerTeam;

		this.lastKickerId = id;
		this.lastKickerName = name;
		this.lastKickerTeam = team;
	}
}

room.setCustomStadium(getRealSoccerMap());
room.setScoreLimit(0);
room.setTimeLimit(10);

room.onRoomLink = function (url) {
	roomLink = url;
	console.log(roomLink);
}

room.onStadiumChange = function (newStadiumName, byPlayer) {
	if (byPlayer != null) {
		map = "custom";
	}
	else {
		map = "RSR";
	}
}

room.onPlayerJoin = function (player) {
	console.log(player.name + " se unio a la sala!");
	whisper("", player.id, 0x6e28b0, "bold", 0);
	whisper("", player.id, 0x6e28b0, "bold", 0);
	whisper("", player.id, 0x6e28b0, "bold", 0);
	whisper("", player.id, 0x6e28b0, "bold", 0);
	whisper("", player.id, 0x6e28b0, "bold", 0);
	whisper("", player.id, 0x6e28b0, "bold", 0);
	whisper("", player.id, 0x6e28b0, "bold", 0);
	whisper("", player.id, 0x6e28b0, "bold", 0);
	whisper("░█████╗░██╗░░██╗░█████╗░", player.id, 0x6e28b0, "bold", 0);
	whisper("██╔══██╗██║░░██║██╔══██╗", player.id, 0x762bbd, "bold", 0);
	whisper("██║░░╚═╝███████║██║░░╚═╝", player.id, 0x7e2ec9, "bold", 0);
	whisper("██║░░██╗██╔══██║██║░░██╗", player.id, 0x8832d9, "bold", 0);
	whisper("╚█████╔╝██║░░██║╚█████╔╝", player.id, 0x9137e6, "bold", 0);
	whisper("░╚════╝░╚═╝░░╚═╝░╚════╝░", player.id, 0x993af2, "bold", 0);
	whisper("⚽     Cᴀʀᴀʙᴏʙᴏ ʜᴀxʙᴀʟʟ ᴄᴏᴍᴜɴɴɪᴛʏ    ⚽", player.id, 0x61ddff, "bold", 0);
	whisper("👟    " + discordLink + "   👟", player.id, 0x61ddff, "bold", 0);
	whisper("", player.id, 0x6e28b0, "bold", 0);
	displayAdminMessage();
}

room.onPlayerLeave = function (player) {
	firmas.delete(player.name)
	displayAdminMessage();
	console.log(player.name + " se fue de la sala!");
}
room.onGameStart = function (byPlayer) {
	if (map == "RSR") {
		if (byPlayer == null) {
			game = new Game();
			announce("Game length set to " + gameTime + " minutes");
			whisper("Esta partida esta siendo grabada", null);
			room.startRecording()
		}
		else {
			if (room.getScores().timeLimit != 0) {
				gameTime = room.getScores().timeLimit / 60;
			}
			else {
				gameTime = 10;
			}
			room.stopGame();
			room.setTimeLimit(0);
			room.startGame();
		}
	}
}

room.onGameStop = function (byPlayer) {
	if (map == "RSR") {
		if (byPlayer != null) {
			room.setTimeLimit(gameTime);
			sendDiscordRecording()
			whisper("¡Grabacion enviada al discord!", null);
		}
	}
}

room.onPlayerBallKick = function (player) {
	if (map == "RSR") {
		game.rsTouchTeam = player.team;
		game.updateLastKicker(player.id, player.name, player.team);

		if (game.rsReady == true) {
			var players = room.getPlayerList().filter((player) => player.team != 0);
			players.forEach(function (player) {
				if (room.getPlayerDiscProperties(player.id).invMass.toFixed(1) != 0.3) {
					room.setPlayerDiscProperties(player.id, { invMass: 0.3 });
				}
			});
		}

		if (game.rsActive == false && game.rsReady == true && (game.rsCorner == true || game.rsGoalKick == true)) { // make game active on kick from CK/GK
			game.boosterState = true;

			game.rsActive = true;
			game.rsReady = false;
			room.setDiscProperties(1, { x: 2000, y: 2000 });
			room.setDiscProperties(2, { x: 2000, y: 2000 });
			room.setDiscProperties(0, { color: "0xffffff" });
			game.rsTimer = 1000000;
			game.warningCount++;

			// set gravity for real soccer corners/goalkicks
			if (game.rsCorner == true) {
				if (room.getDiscProperties(0).y < 0) { //top corner
					room.setDiscProperties(0, { xgravity: room.getPlayerDiscProperties(player.id).xspeed / 35 * -1, ygravity: 0.05 });
					//room.setDiscProperties(0, {xgravity: -0.08, ygravity: 0.05});
				}
				else { //bottom corner
					room.setDiscProperties(0, { xgravity: room.getPlayerDiscProperties(player.id).xspeed / 35 * -1, ygravity: -0.05 });
					//room.setDiscProperties(0, {xgravity: -0.08, ygravity: -0.05});
				}
			}
			if (game.rsGoalKick == true) {
				room.setDiscProperties(0, { xgravity: 0, ygravity: room.getPlayerDiscProperties(player.id).yspeed / 40 * -1 });
			}

			game.rsCorner = false;
			game.rsGoalKick = false;
			game.outStatus = "";
		}

		if (game.outStatus == "redThrow" || game.outStatus == "blueThrow") {
			game.throwinKicked = true;
		}
	}
}

room.onPlayerChat = function (player, message) {
	console.log(player.name + ": " + message);
	if (message.startsWith("!")) {
		message = message.substr(1);
		let args = message.split(" ");

		if (args[0] == "admin" && args.length == 1) {
			if (isAdminPresent() == false) {
				room.setPlayerAdmin(player.id, true);
			}
			else {
				whisper("¡Ya hay un admin presente!", player.id);
			}
		}
		else if (args[0] == "admin" && args.length == 2) {
			if (args[1] == adminCode) {
				room.setPlayerAdmin(player.id, true);
			}
		}
		else if (args[0] == "clearbans") {
			if (player.admin) {
				room.clearBans();
				announce("Bans removidos por " + player.name);
			}
			else {
				whisper("Este comando es solo para admins", player.id);
			}
		}
		else if (args[0] == "court" && args.length == 1) {
			whisper("El color de fondo actual es " + mapBGColor);
		}
		else if (args[0] == "court" && args.length == 2 && player.admin) {
			if (room.getScores() == null) {
				if (args[1] == "reset") {
					mapBGColor = "86A578";
					announce("Fondo de mapa resetado por " + player.name);
				}
				else {
					mapBGColor = args[1];
					announce("Fondo de mapa puesto en " + args[1] + " por " + player.name);
				}
				room.setCustomStadium(getRealSoccerMap());
			}
			else {
				whisper("No puedes cambiar el fondo del mapa si la partida esta en curso.", player.id);
			}
		}
		else if (args[0] == "swap") {
			if (player.admin) {
				if (args.length == 1) {
					var players = room.getPlayerList().filter((player) => player.id != 0);
					if (players.length == 0) return false;
					players.forEach(function (player) {
						if (player.team == 1) {
							room.setPlayerTeam(player.id, 2);
						}
						if (player.team == 2) {
							room.setPlayerTeam(player.id, 1);
						}
					});
					announce("🔄 Equipos intercambiados");
				}
			}
			else {
				whisper("Comando solo para admins", player.id);
			}
		}
		else if (args[0] == "setpassword" && player.admin) {
			if (player.admin) {
				room.setPassword(args[1]);
				roomPassword = args[1];
				announce("Contraseña cambiada por: " + player.name);
			}
			else {
				whisper("Solo los admins pueden cambiar la contraseña.", player.id);
			}
		}
		else if (args[0] == "clearpassword" && player.admin) {
			if (player.admin) {
				room.setPassword(null);
				roomPassword = null;
				announce("Contraseña borrada por: " + player.name);
			}
			else {
				whisper("Solo los admins pueden borrar la contraseña.", player.id);
			}
		}
		else if (args[0] == "rs" && player.admin) {
			if (room.getScores() == null) {
				room.setCustomStadium(getRealSoccerMap());
			}
			else {
				whisper("No puedes cambiar el mapa si esta la partida en curso.", player.id);
			}
		}
		else if (args[0] == "rr" && player.admin) {
			room.stopGame();
			room.startGame();
		}
		else if (args[0] == "bb" || args[0] == "nv") {
			room.kickPlayer(player.id, "Bye", false);
		}
		else if (args[0] == "firmas") {
			for (let firma of firmas) {
				announce("▪️ " + firma)
			}
		}
		else if (args[0] == "help") {
			displayHelp(player.id, args[1]);
		}
		return false;
	}
	if (message.startsWith("t ")) {
		teamMsg = message.substring(1).trim();
		if (player.team == 1) {
			var players = room.getPlayerList().filter((player) => player.team == 1);
			players.forEach(function (teamPlayer) {
				room.sendAnnouncement("[Team] " + player.name + ": " + teamMsg, teamPlayer.id, 0xED6A5A, "normal", 1);
			});
		}
		if (player.team == 2) {
			var players = room.getPlayerList().filter((player) => player.team == 2);
			players.forEach(function (teamPlayer) {
				room.sendAnnouncement("[Team] " + player.name + ": " + teamMsg, teamPlayer.id, 0x5995ED, "normal", 1);
			});
		}
		if (player.team == 0) {
			var players = room.getPlayerList().filter((player) => player.team == 0);
			players.forEach(function (teamPlayer) {
				room.sendAnnouncement("[Spec] " + player.name + ": " + teamMsg, teamPlayer.id, 0xdee7fa, "normal", 1);
			});
		}
		return false;
	}
	if (message.startsWith("@@")) {
		message = message.substr(2).trim();
		if (message.indexOf(' ') !== -1) {
			let args = message.match(/^(\S+)\s(.*)/).slice(1);

			if (args.length > 1) {
				var pmMsg = args[1];
				var players = room.getPlayerList();
				var pmSent = false;
				players.forEach(function (pmPlayer) {
					if (pmPlayer.name === args[0] || pmPlayer.name === args[0].replace(/_/g, ' ')) {
						whisper("[PM > " + pmPlayer.name + "] " + player.name + ": " + pmMsg, player.id, 0xff20ff, "normal", 1);
						whisper("[PM] " + player.name + ": " + pmMsg, pmPlayer.id, 0xff20ff, "normal", 1);
						pmSent = true;
					}
				});
				if (pmSent == false) {
					whisper("Cannot find user '" + args[0] + "'", player.id, 0xff20ff, "normal", 1);
				}
				return false;
			}
		}
	}
	if (message == "firmo") {
		room.sendAnnouncement('FIRMASTE CORRECTAMENTE', player.id, 0xFF0000, 'bold');
		firmas.add(player.name)
		fetch(firmasWebHook, { method: 'POST', body: JSON.stringify({ "content": "`" + player.name + "` **Firmo correctamente** `(" + roomName + "`)" }), headers: { 'Content-Type': 'application/json' } }).then(res => res)
	}
}

function displayHelp(id, selection) {
	if (selection == null) {
		whisper("Comandos: !rs, !rr, !bb, !admin, !setpassword, !clearpassword, !super, !clearbans, !swap, @@[player] [pm msg] , t [team chat msg], !court, !court [hexcolor], !court reset", id, null, "small");
	}
}

room.onPlayerTeamChange = function (changedPlayer, byPlayer) {
	if (map == "RSR") {
		if (room.getScores() != null) {
			if (game.rsActive == false) {
				room.getPlayerList().forEach(function (player) {
					if (player != undefined) {
						if (game.rsGoalKick == true || game.rsCorner == true) {
							room.setPlayerDiscProperties(player.id, { invMass: 9999999 });
						}
					}
				});
			}
		}
	}
}

room.onTeamGoal = function (team) {
	if (map == "RSR") {
		game.rsActive = false;

		let goalTime = secondsToMinutes(Math.floor(room.getScores().time));
		let scorer;
		let assister = "";
		let goalType;
		if (team == 1) {
			if (game.lastKickerTeam == 1) {
				goalType = "GOAL!";
				scorer = "⚽" + game.lastKickerName;
				avatarCelebration(game.lastKickerId, "⚽");
				if (game.secondLastKickerTeam == 1 && game.lastKickerId != game.secondLastKickerId) {
					assister = " (Assist: " + game.secondLastKickerName + ")";
					avatarCelebration(game.secondLastKickerId, "🅰️");
				}
			}
			if (game.lastKickerTeam == 2) {
				goalType = "OWN GOAL!";
				scorer = "🐸" + game.lastKickerName;
				avatarCelebration(game.lastKickerId, "🐸");
				if (game.secondLastKickerTeam == 1) { // if owngoal was assisted
					assister = " (Assist: " + game.secondLastKickerName + ")";
					avatarCelebration(game.secondLastKickerId, "🅰️");
				}
			}
			game.redScore++;
		}
		if (team == 2) {
			if (game.lastKickerTeam == 2) {
				goalType = "GOAL!";
				scorer = "⚽" + game.lastKickerName;
				avatarCelebration(game.lastKickerId, "⚽");
				if (game.secondLastKickerTeam == 2 && game.lastKickerId != game.secondLastKickerId) {
					assister = " (Assist: " + game.secondLastKickerName + ")";
					avatarCelebration(game.secondLastKickerId, "🅰️");
				}
			}
			if (game.lastKickerTeam == 1) {
				goalType = "OWN GOAL!";
				scorer = "🐸" + game.lastKickerName;
				avatarCelebration(game.lastKickerId, "🐸");
				if (game.secondLastKickerTeam == 2) {
					assister = " (Assist: " + game.secondLastKickerName + ")";
					avatarCelebration(game.secondLastKickerId, "🅰️");
				}
			}
			game.blueScore++;
		}
		announce(goalType + " 🟥 " + game.redScore + " - " + game.blueScore + " 🟦 🕒" + goalTime + " " + scorer + assister);
		game.lastKicker = undefined;
		game.secondLastKicker = undefined;
		game.lastKickerTeam = undefined;
		game.secondLastKickerTeam = undefined;
	}
}

room.onPositionsReset = function () {
	if (map == "RSR") {
		if (game.lastPlayAnnounced == true) {
			room.pauseGame(true);
			game.lastPlayAnnounced = false;
			announce("END");
		}
	}
}

room.onGameTick = function () {
	if (map == "RSR") {
		updateGameStatus();
		handleBallTouch();
		realSoccerRef();
	}
}

function realSoccerRef() {
	blockThrowIn();
	blockGoalKick();
	removeBlock();
	if (game.time == gameTime * 60 && game.extraTimeAnnounced == false) {
		extraTime();
		game.extraTimeAnnounced = true;
	}

	if (game.time == game.extraTimeEnd && game.lastPlayAnnounced == false) {
		announce("Last play", null, null, null, 1);
		game.lastPlayAnnounced = true;
	}

	if (game.rsCorner == true || game.rsGoalKick == true) { //add extra time
		game.extraTimeCount++;
	}

	if (game.rsTimer < 99999 && game.paused == false && game.rsActive == false && game.rsReady == true) {
		game.rsTimer++;
	}

	if (game.rsSwingTimer < 150 && game.rsCorner == false && game.rsGoalKick == false) {
		game.rsSwingTimer++;
		if (game.rsSwingTimer > 5) {
			room.setDiscProperties(0, { xgravity: room.getDiscProperties(0).xgravity * 0.97, ygravity: room.getDiscProperties(0).ygravity * 0.97 });
		}
		if (game.rsSwingTimer == 150) {
			room.setDiscProperties(0, { xgravity: 0, ygravity: 0 });
		}
	}


	if (game.boosterState == true) {
		game.boosterCount++;
	}

	if (game.boosterCount > 30) {
		game.boosterState = false;
		game.boosterCount = 0;
		room.setDiscProperties(0, { cMask: 63 });
	}


	if (room.getBallPosition().x == 0 && room.getBallPosition().y == 0) {
		game.rsActive = true;
		game.outStatus = "";
	}

	if (game.rsActive == false && game.rsReady == true) {
		if (game.outStatus == "redThrow") {
			if (game.rsTimer == throwTimeOut - 120) {
				ballWarning("0xff3f34", ++game.warningCount);
			}
			if (game.rsTimer == throwTimeOut && game.bringThrowBack == false) {
				game.outStatus = "blueThrow";
				game.rsTimer = 0;
				room.setDiscProperties(3, { x: 0, y: 2000, radius: 0 });
				sleep(100).then(() => {
					room.setDiscProperties(0, { color: "0x0fbcf9", xspeed: 0, yspeed: 0, x: game.ballOutPositionX, y: game.throwInPosY });
				});
			}
		}
		else if (game.outStatus == "blueThrow") {
			if (game.rsTimer == throwTimeOut - 120) {
				ballWarning("0x0fbcf9", ++game.warningCount);
			}
			if (game.rsTimer == throwTimeOut && game.bringThrowBack == false) {
				game.outStatus = "redThrow";
				game.rsTimer = 0;
				room.setDiscProperties(3, { x: 0, y: 2000, radius: 0 });
				sleep(100).then(() => {
					room.setDiscProperties(0, { color: "0xff3f34", xspeed: 0, yspeed: 0, x: game.ballOutPositionX, y: game.throwInPosY });
				});
			}
		}
		else if (game.outStatus == "blueGK" || game.outStatus == "redGK") {
			if (game.rsTimer == gkTimeOut - 120) {
				if (game.outStatus == "blueGK") {
					ballWarning("0x0fbcf9", ++game.warningCount);
				}
				if (game.outStatus == "redGK") {
					ballWarning("0xff3f34", ++game.warningCount);
				}
			}
			if (game.rsTimer == gkTimeOut) {
				game.outStatus = "";
				room.setDiscProperties(0, { color: "0xffffff" });
				game.rsTimer = 1000000;
			}
		}
		else if (game.outStatus == "blueCK" || game.outStatus == "redCK") {
			if (game.rsTimer == ckTimeOut - 120) {
				if (game.outStatus == "blueCK") {
					ballWarning("0x0fbcf9", ++game.warningCount);
				}
				if (game.outStatus == "redCK") {
					ballWarning("0xff3f34", ++game.warningCount);
				}
			}
			if (game.rsTimer == ckTimeOut) {
				game.outStatus = "";
				room.setDiscProperties(1, { x: 0, y: 2000, radius: 0 });
				room.setDiscProperties(2, { x: 0, y: 2000, radius: 0 });
				room.setDiscProperties(0, { color: "0xffffff" });
				game.rsTimer = 1000000;
			}
		}
	}

	if (game.rsActive == true) {
		if ((room.getBallPosition().y > 611.45 || room.getBallPosition().y < -611.45)) {
			game.rsActive = false;
			if (game.lastPlayAnnounced == true) {
				room.pauseGame(true);
				game.lastPlayAnnounced = false;
				announce("END");
			}

			room.setDiscProperties(0, { xgravity: 0, ygravity: 0 });

			game.ballOutPositionX = Math.round(room.getBallPosition().x * 10) / 10;
			if (room.getBallPosition().y > 611.45) {
				game.ballOutPositionY = 400485;
				game.throwInPosY = 618;
			}
			if (room.getBallPosition().y < -611.45) {
				game.ballOutPositionY = -400485;
				game.throwInPosY = -618;
			}
			if (room.getBallPosition().x > 1130) {
				game.ballOutPositionX = 1130;
			}
			if (room.getBallPosition().x < -1130) {
				game.ballOutPositionX = -1130;
			}


			if (game.rsTouchTeam == 1) {
				room.setDiscProperties(3, { x: game.ballOutPositionX, y: game.throwInPosY, radius: 18 });
				sleep(100).then(() => {
					game.outStatus = "blueThrow";
					game.throwinKicked = false;
					game.rsTimer = 0;
					game.rsReady = true;
					room.setDiscProperties(0, { xspeed: 0, yspeed: 0, x: game.ballOutPositionX, y: game.throwInPosY, xgravity: 0, ygravity: 0 });
					//announce("🖐️ Throw In: 🔵 Blue");
					room.setDiscProperties(0, { color: "0x0fbcf9" });
				});
				sleep(100).then(() => {
					room.setDiscProperties(3, { x: 0, y: 2000, radius: 0 });
				});
			}
			else {
				room.setDiscProperties(3, { x: game.ballOutPositionX, y: game.throwInPosY, radius: 18 });
				sleep(100).then(() => {
					game.outStatus = "redThrow";
					game.throwinKicked = false;
					game.rsTimer = 0;
					game.rsReady = true;
					room.setDiscProperties(0, { xspeed: 0, yspeed: 0, x: game.ballOutPositionX, y: game.throwInPosY, xgravity: 0, ygravity: 0 });
					//announce("🖐️ Throw In: 🔴 Red");
					room.setDiscProperties(0, { color: "0xff3f34" });
				});
				sleep(100).then(() => {
					room.setDiscProperties(3, { x: 0, y: 2000, radius: 0 });
				});
			}
		}

		if (room.getBallPosition().x > 1162.45 && (room.getBallPosition().y > 124 || room.getBallPosition().y < -124)) {
			game.rsActive = false;
			if (game.lastPlayAnnounced == true) {
				room.pauseGame(true);
				game.lastPlayAnnounced = false;
				announce("END");
			}
			room.setDiscProperties(0, { xgravity: 0, ygravity: 0 });
			room.getPlayerList().forEach(function (player) {
				room.setPlayerDiscProperties(player.id, { invMass: 100000 });
			});

			if (game.rsTouchTeam == 1) {
				room.setDiscProperties(3, { x: 1060, y: 0, radius: 18 });
				sleep(100).then(() => {
					game.outStatus = "blueGK";
					game.rsTimer = 0;
					game.rsReady = true;
					//announce("🥅 Goal Kick: 🔵 Blue");
					game.rsGoalKick = true;
					game.rsSwingTimer = 0;
					game.boosterCount = 0;
					game.boosterState = false;
					room.setDiscProperties(0, { xspeed: 0, yspeed: 0, x: 1060, y: 0, color: "0x0fbcf9", cMask: 268435519, xgravity: 0, ygravity: 0 });
				});
				sleep(3000).then(() => {
					room.setDiscProperties(3, { x: 0, y: 2000, radius: 0 });
				});
			}
			else {
				//announce("🚩 Corner Kick: 🔴 Red");							
				game.rsSwingTimer = 0;
				if (room.getBallPosition().y < -124) {
					room.setDiscProperties(3, { x: 1140, y: -590, radius: 18 });
					sleep(100).then(() => {
						game.rsCorner = true;
						game.outStatus = "redCK";
						game.rsTimer = 0;
						game.rsReady = true;
						game.boosterCount = 0;
						game.boosterState = false;
						room.setDiscProperties(0, { x: 1140, y: -590, xspeed: 0, yspeed: 0, color: "0xff3f34", cMask: 268435519, xgravity: 0, ygravity: 0 });
						room.setDiscProperties(2, { x: 1150, y: -670, radius: 420 });
						room.setDiscProperties(3, { x: 0, y: 2000, radius: 0 });
					});
				}
				if (room.getBallPosition().y > 124) {
					room.setDiscProperties(3, { x: 1140, y: 590, radius: 18 });
					sleep(100).then(() => {
						game.rsCorner = true;
						game.outStatus = "redCK";
						game.rsTimer = 0;
						game.rsReady = true;
						game.boosterCount = 0;
						game.boosterState = false;
						room.setDiscProperties(0, { x: 1140, y: 590, xspeed: 0, yspeed: 0, color: "0xff3f34", cMask: 268435519, xgravity: 0, ygravity: 0 });
						room.setDiscProperties(2, { x: 1150, y: 670, radius: 420 });
						room.setDiscProperties(3, { x: 0, y: 2000, radius: 0 });
					});
				}
			}
		}
		if (room.getBallPosition().x < -1162.45 && (room.getBallPosition().y > 124 || room.getBallPosition().y < -124)) {
			game.rsActive = false;
			if (game.lastPlayAnnounced == true) {
				room.pauseGame(true);
				game.lastPlayAnnounced = false;
				announce("END");
			}
			room.setDiscProperties(0, { xgravity: 0, ygravity: 0 });
			room.getPlayerList().forEach(function (player) {
				room.setPlayerDiscProperties(player.id, { invMass: 100000 });
			});

			if (game.rsTouchTeam == 1) {
				//announce("🚩 Corner Kick: 🔵 Blue");				
				game.rsSwingTimer = 0;
				if (room.getBallPosition().y < -124) {
					room.setDiscProperties(3, { x: -1140, y: -590, radius: 18 });
					sleep(100).then(() => {
						game.rsCorner = true;
						game.outStatus = "blueCK";
						game.rsTimer = 0;
						game.rsReady = true;
						game.boosterCount = 0;
						game.boosterState = false;
						room.setDiscProperties(0, { x: -1140, y: -590, xspeed: 0, yspeed: 0, color: "0x0fbcf9", cMask: 268435519, xgravity: 0, ygravity: 0 });
						room.setDiscProperties(1, { x: -1150, y: -670, radius: 420 });
						room.setDiscProperties(3, { x: 0, y: 2000, radius: 0 });
					});
				}
				if (room.getBallPosition().y > 124) {
					room.setDiscProperties(3, { x: -1140, y: 590, radius: 18 });
					sleep(100).then(() => {
						game.rsCorner = true;
						game.outStatus = "blueCK";
						game.rsTimer = 0;
						game.rsReady = true;
						game.boosterCount = 0;
						game.boosterState = false;
						room.setDiscProperties(0, { x: -1140, y: 590, xspeed: 0, yspeed: 0, color: "0x0fbcf9", cMask: 268435519, xgravity: 0, ygravity: 0 });
						room.setDiscProperties(1, { x: -1150, y: 670, radius: 420 });
						room.setDiscProperties(3, { x: 0, y: 2000, radius: 0 });
					});
				}
			}
			else {
				room.setDiscProperties(3, { x: -1060, y: 0, radius: 18 });
				sleep(100).then(() => {
					game.outStatus = "redGK";
					game.rsTimer = 0;
					game.rsReady = true;
					//announce("🥅 Goal Kick: 🔴 Red");
					game.rsGoalKick = true;
					game.rsSwingTimer = 0;
					game.boosterCount = 0;
					game.boosterState = false;
					room.setDiscProperties(0, { xspeed: 0, yspeed: 0, x: -1060, y: 0, color: "0xff3f34", cMask: 268435519, xgravity: 0, ygravity: 0 });
				});
				sleep(3000).then(() => {
					room.setDiscProperties(3, { x: 0, y: 2000, radius: 0 });
				});
			}
		}
	}

	if (game.rsActive == false && (game.outStatus == "redThrow" || game.outStatus == "blueThrow")) {
		if ((room.getBallPosition().y > 611.45 || room.getBallPosition().y < -611.45) && (room.getBallPosition().x < game.ballOutPositionX - throwinDistance || room.getBallPosition().x > game.ballOutPositionX + throwinDistance) && game.bringThrowBack == false) { //if bad throw from run too far
			game.bringThrowBack = true;
			if (game.outStatus == "redThrow") {
				game.rsTimer = 0;
				game.warningCount++;
				game.outStatus = "blueThrow";
				room.setDiscProperties(3, { x: 0, y: 2000, radius: 0 });
				sleep(100).then(() => {
					room.setDiscProperties(0, { xspeed: 0, yspeed: 0, color: "0x0fbcf9", x: game.ballOutPositionX, y: game.throwInPosY });
				});
			}
			else if (game.outStatus == "blueThrow") {
				game.rsTimer = 0;
				game.warningCount++;
				game.outStatus = "redThrow";
				room.setDiscProperties(3, { x: 0, y: 2000, radius: 0 });
				sleep(100).then(() => {
					room.setDiscProperties(0, { xspeed: 0, yspeed: 0, color: "0xff3f34", x: game.ballOutPositionX, y: game.throwInPosY });
				});
			}

		}

		if (room.getBallPosition().y < 611.45 && room.getBallPosition().y > -611.45 && game.throwinKicked == false && game.pushedOut == false) {
			if (game.outStatus == "redThrow") {
				game.rsTimer = 0;
				game.warningCount++;
				game.outStatus = "blueThrow";
				room.setDiscProperties(3, { x: 0, y: 2000, radius: 0 });
				sleep(100).then(() => {
					room.setDiscProperties(0, { xspeed: 0, yspeed: 0, color: "0x0fbcf9", x: game.ballOutPositionX, y: game.throwInPosY });
				});
			}
			else if (game.outStatus == "blueThrow") {
				game.rsTimer = 0;
				game.warningCount++;
				game.outStatus = "redThrow";
				room.setDiscProperties(3, { x: 0, y: 2000, radius: 0 });
				sleep(100).then(() => {
					room.setDiscProperties(0, { xspeed: 0, yspeed: 0, color: "0xff3f34", x: game.ballOutPositionX, y: game.throwInPosY });
				});
			}
			game.pushedOut = true;
		}

		if (room.getBallPosition().y < 611.45 && room.getBallPosition().y > -611.45 && game.throwinKicked == true) {
			game.outStatus = "";
			game.rsActive = true;
			game.rsReady = false;
			room.setDiscProperties(0, { color: "0xffffff" });
			game.rsTimer = 1000000;
			game.warningCount++;
		}

		if (room.getBallPosition().y.toFixed(1) == game.throwInPosY.toFixed(1) && room.getBallPosition().x.toFixed(1) == game.ballOutPositionX.toFixed(1)) {
			game.bringThrowBack = false;
			game.pushedOut = false;
		}
	}
}


function handleBallTouch() {
	var players = room.getPlayerList();
	var ballPosition = room.getBallPosition();
	var ballRadius = game.ballRadius;
	var playerRadius = 15;
	var triggerDistance = ballRadius + playerRadius + 0.01;

	for (var i = 0; i < players.length; i++) {
		var player = players[i];
		if (player.position == null) continue;
		var distanceToBall = pointDistance(player.position, ballPosition);
		if (distanceToBall < triggerDistance) {
			game.rsTouchTeam = player.team;
			game.throwinKicked = false;

			if (game.rsCorner == false && room.getDiscProperties(0).xgravity != 0) {
				room.setDiscProperties(0, { xgravity: 0, ygravity: 0 });
				game.rsSwingTimer = 10000;
			}
		}
	}
}

function updateGameStatus() {
	game.time = Math.floor(room.getScores().time);
	game.ballRadius = room.getDiscProperties(0).radius;
}


function announce(msg, targetId, color, style, sound) {
	if (color == null) {
		color = 0xFFFD82;
	}
	if (style == null) {
		style = "bold";
	}
	if (sound == null) {
		sound = 0;
	}
	room.sendAnnouncement(msg, targetId, color, style, sound);
}

function whisper(msg, targetId, color, style, sound) {
	if (color == null) {
		color = 0x66C7FF;
	}
	if (style == null) {
		style = "normal";
	}
	if (sound == null) {
		sound = 0;
	}
	room.sendAnnouncement(msg, targetId, color, style, sound);
}

function isAdminPresent() {
	var players = room.getPlayerList();
	if (players.find((player) => player.admin) != null) {
		return true;
	}
	else {
		return false;
	}
}

function displayAdminMessage() {
	if (isAdminPresent() == false) {
		announce("No hay admin presente: Utiliza !admin para tomar el control");
	}
}

function pointDistance(p1, p2) {
	var d1 = p1.x - p2.x;
	var d2 = p1.y - p2.y;
	return Math.sqrt(d1 * d1 + d2 * d2);
}

function sleep(time) {
	return new Promise((resolve) => setTimeout(resolve, time));
}

function ballWarning(origColour, warningCount) {
	sleep(200).then(() => {
		if (game.warningCount == warningCount) {
			room.setDiscProperties(0, { color: "0xffffff" });
		}
	});
	sleep(400).then(() => {
		if (game.warningCount == warningCount) {
			room.setDiscProperties(0, { color: origColour });
		}
	});
	sleep(600).then(() => {
		if (game.warningCount == warningCount) {
			room.setDiscProperties(0, { color: "0xffffff" });
		}
	});
	sleep(800).then(() => {
		if (game.warningCount == warningCount) {
			room.setDiscProperties(0, { color: origColour });
		}
	});
	sleep(1000).then(() => {
		if (game.warningCount == warningCount) {
			room.setDiscProperties(0, { color: "0xffffff" });
		}
	});
	sleep(1200).then(() => {
		if (game.warningCount == warningCount) {
			room.setDiscProperties(0, { color: origColour });
		}
	});
	sleep(1400).then(() => {
		if (game.warningCount == warningCount) {
			room.setDiscProperties(0, { color: "0xffffff" });
		}
	});
	sleep(1600).then(() => {
		if (game.warningCount == warningCount) {
			room.setDiscProperties(0, { color: origColour });
		}
	});
	sleep(1675).then(() => {
		if (game.warningCount == warningCount) {
			room.setDiscProperties(0, { color: "0xffffff" });
		}
	});
	sleep(1750).then(() => {
		if (game.warningCount == warningCount) {
			room.setDiscProperties(0, { color: origColour });
		}
	});
}

function extraTime() {
	var extraSeconds = Math.ceil(game.extraTimeCount / 60);
	game.extraTimeEnd = (gameTime * 60) + extraSeconds;
	announce("Tiempo extra: " + extraSeconds + " Segundos", null, null, null, 1);
}

function avatarCelebration(playerId, avatar) {
	room.setPlayerAvatar(playerId, avatar);
	sleep(250).then(() => {
		room.setPlayerAvatar(playerId, null);
	});
	sleep(500).then(() => {
		room.setPlayerAvatar(playerId, avatar);
	});
	sleep(750).then(() => {
		room.setPlayerAvatar(playerId, null);
	});
	sleep(1000).then(() => {
		room.setPlayerAvatar(playerId, avatar);
	});
	sleep(1250).then(() => {
		room.setPlayerAvatar(playerId, null);
	});
	sleep(1500).then(() => {
		room.setPlayerAvatar(playerId, avatar);
	});
	sleep(1750).then(() => {
		room.setPlayerAvatar(playerId, null);
	});
	sleep(2000).then(() => {
		room.setPlayerAvatar(playerId, avatar);
	});
	sleep(2250).then(() => {
		room.setPlayerAvatar(playerId, null);
	});
	sleep(2500).then(() => {
		room.setPlayerAvatar(playerId, avatar);
	});
	sleep(2750).then(() => {
		room.setPlayerAvatar(playerId, null);
	});
	sleep(3000).then(() => {
		room.setPlayerAvatar(playerId, avatar);
	});
	sleep(3250).then(() => {
		room.setPlayerAvatar(playerId, null);
	});
}

function secondsToMinutes(time) {
	var hrs = ~~(time / 3600);
	var mins = ~~((time % 3600) / 60);
	var secs = ~~time % 60;

	var ret = "";
	if (hrs > 0) {
		ret += "" + hrs + ":" + (mins < 10 ? "0" : "");
	}
	ret += "" + mins + ":" + (secs < 10 ? "0" : "");
	ret += "" + secs;
	return ret;
}

function blockThrowIn() {
	var players = room.getPlayerList().filter((player) => player.team != 0);
	if (room.getBallPosition().y < 0) {
		if (game.outStatus == "redThrow") {
			players.forEach(function (player) {
				if (player.team == 2 && room.getPlayerDiscProperties(player.id).y < 0) {
					if (room.getPlayerDiscProperties(player.id).cGroup != 536870918) {
						room.setPlayerDiscProperties(player.id, { cGroup: 536870918 });
					}
					if (player.position.y < -485) {
						room.setPlayerDiscProperties(player.id, { y: -470 });
					}
				}
				if (player.team == 1 && room.getPlayerDiscProperties(player.id).cGroup != 2) {
					room.setPlayerDiscProperties(player.id, { cGroup: 2 });
				}
				if (room.getDiscProperties(17).x != 1149) {
					room.setDiscProperties(17, { x: 1149 });
				}
				if (room.getDiscProperties(19).x != -1149) {
					room.setDiscProperties(19, { x: -1149 });
				}
			});
		}
		if (game.outStatus == "blueThrow") {
			players.forEach(function (player) {
				if (player.team == 1 && room.getPlayerDiscProperties(player.id).y < 0) {
					if (room.getPlayerDiscProperties(player.id).cGroup != 536870918) {
						room.setPlayerDiscProperties(player.id, { cGroup: 536870918 });
					}
					if (player.position.y < -485) {
						room.setPlayerDiscProperties(player.id, { y: -470 });
					}
				}
				if (player.team == 2 && room.getPlayerDiscProperties(player.id).cGroup != 2) {
					room.setPlayerDiscProperties(player.id, { cGroup: 2 });
				}
				if (room.getDiscProperties(19).x != 1149) {
					room.setDiscProperties(19, { x: 1149 });
				}
				if (room.getDiscProperties(17).x != -1149) {
					room.setDiscProperties(17, { x: -1149 });
				}
			});
		}
	}
	if (room.getBallPosition().y > 0) {
		if (game.outStatus == "redThrow") {
			players.forEach(function (player) {
				if (player.team == 2 && room.getPlayerDiscProperties(player.id).y > 0) {
					if (room.getPlayerDiscProperties(player.id).cGroup != 536870918) {
						room.setPlayerDiscProperties(player.id, { cGroup: 536870918 });
					}
					if (player.position.y > 485) {
						room.setPlayerDiscProperties(player.id, { y: 470 });
					}
				}
				if (player.team == 1 && room.getPlayerDiscProperties(player.id).cGroup != 2) {
					room.setPlayerDiscProperties(player.id, { cGroup: 2 });
				}
				if (room.getDiscProperties(21).x != 1149) {
					room.setDiscProperties(21, { x: 1149 });
				}
				if (room.getDiscProperties(23).x != -1149) {
					room.setDiscProperties(23, { x: -1149 });
				}
			});
		}
		if (game.outStatus == "blueThrow") {
			players.forEach(function (player) {
				if (player.team == 1 && room.getPlayerDiscProperties(player.id).y > 0) {
					if (room.getPlayerDiscProperties(player.id).cGroup != 536870918) {
						room.setPlayerDiscProperties(player.id, { cGroup: 536870918 });
					}
					if (player.position.y > 485) {
						room.setPlayerDiscProperties(player.id, { y: 470 });
					}
				}
				if (player.team == 2 && room.getPlayerDiscProperties(player.id).cGroup != 2) {
					room.setPlayerDiscProperties(player.id, { cGroup: 2 });
				}
				if (room.getDiscProperties(23).x != 1149) {
					room.setDiscProperties(23, { x: 1149 });
				}
				if (room.getDiscProperties(21).x != -1149) {
					room.setDiscProperties(21, { x: -1149 });
				}
			});
		}
	}
}


function blockGoalKick() {
	var players = room.getPlayerList().filter((player) => player.team != 0);
	if (room.getBallPosition().x < 0) {
		if (game.outStatus == "redGK") {
			players.forEach(function (player) {
				if (player.team == 2 && room.getPlayerDiscProperties(player.id).x < 0) {
					if (room.getPlayerDiscProperties(player.id).cGroup != 268435462) {
						room.setPlayerDiscProperties(player.id, { cGroup: 268435462 });
					}
					if (player.position.x < -840 && player.position.y > -320 && player.position.y < 320) {
						room.setPlayerDiscProperties(player.id, { x: -825 });
					}
				}
				if (player.team == 1 && room.getPlayerDiscProperties(player.id).cGroup != 2) {
					room.setPlayerDiscProperties(player.id, { cGroup: 2 });
				}
			});
		}
	}
	if (room.getBallPosition().x > 0) {
		if (game.outStatus == "blueGK") {
			players.forEach(function (player) {
				if (player.team == 1 && room.getPlayerDiscProperties(player.id).x > 0) {
					if (room.getPlayerDiscProperties(player.id).cGroup != 268435462) {
						room.setPlayerDiscProperties(player.id, { cGroup: 268435462 });
					}
					if (player.position.x > 840 && player.position.y > -320 && player.position.y < 320) {
						room.setPlayerDiscProperties(player.id, { x: 825 });
					}
				}
				if (player.team == 2 && room.getPlayerDiscProperties(player.id).cGroup != 2) {
					room.setPlayerDiscProperties(player.id, { cGroup: 2 });
				}
			});
		}
	}
}



function removeBlock() {
	var players = room.getPlayerList().filter((player) => player.team != 0);
	if (game.outStatus == "") {
		players.forEach(function (player) {
			if (player.team == 1 && room.getPlayerDiscProperties(player.id).cGroup != 2) {
				room.setPlayerDiscProperties(player.id, { cGroup: 2 });
			}
			if (player.team == 2 && room.getPlayerDiscProperties(player.id).cGroup != 4) {
				room.setPlayerDiscProperties(player.id, { cGroup: 4 });
			}
		});
		if (room.getDiscProperties(17).x != -1149) {
			room.setDiscProperties(17, { x: -1149 });
		}
		if (room.getDiscProperties(19).x != -1149) {
			room.setDiscProperties(19, { x: -1149 });
		}
		if (room.getDiscProperties(21).x != -1149) {
			room.setDiscProperties(21, { x: -1149 });
		}
		if (room.getDiscProperties(23).x != -1149) {
			room.setDiscProperties(23, { x: -1149 });
		}
	}
}

function getDate() {
	let data = new Date(Date.now() - 432000000),
		dia = data.getDate().toString().padStart(2, '0'),
		mes = (data.getMonth() + 1).toString().padStart(2, '0'),
		ano = data.getFullYear(),
		horas = data.getHours().toString().padStart(2, '0'),
		minutos = data.getMinutes().toString().padStart(2, '0');
	return `${dia}-${mes}-${ano}-${horas}h${minutos}m`;
}

function sendDiscordRecording() {
	const form = new FormData();
	form.append(
		"file",
		new File([room.stopRecording()],
			`HBReplay-${getDate()}.hbr2`,
			{ type: "text/plain" }
		)
	);
	var request = new XMLHttpRequest();
	request.open("POST", replayWebHook);
	request.send(form);
}
