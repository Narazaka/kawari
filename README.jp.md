�v���O���}�u����AI �ؘa�� Phase 8.2.8

#����͉��ł���


�ؘa�� Phase8 ���������[�X�łł��B
���C�Z���X���n�߁A�V�d�l�Ɋւ��邩�Ȃ�̏�񂪃h�L�������g������Ă��܂��B
document/index.html���A���g�p�̃u���E�U�ł����������B

�f�B���N�g���\���͈ȉ��̂悤�ɂȂ��Ă��܂��B

    kawari-828/       �c�c �v���W�F�N�g���[�g
           readme.1st     �c�c ���̕���
           license.txt    �c�c �C��BSD���C�Z���X��

           bin/           �c�c �e����s�t�@�C��
               shiori.dll         �c�c SHIORI (�x�T�u�V�X�e��)
               kosui.exe          �c�c �K�� (�f�o�b�O�p�R���\�[���A�v��)
               kawari_encode2.exe �c�c �����Í����c�[��
               kawari_decode2.exe �c�c �����������c�[��

           document/      �c�c �h�L�������g
               index.html         �c�c �h�L�������g�g�b�v�y�[�W

           build/         �c�c �r���h��
               BUILD.TXT          �c�c �r���h���@
               contrib/           �c�c ��荞�񂾃p�b�`

#���l

�����[�X�ł̃R���p�C����Minimalist GNU Win32���ōs���Ă��܂��B

2008/03/30
KAWARI Developer Team (Meister/Nise-Meister/Sato/Shino/Suikyo)


#ChangeLog

2008/03/30 Phase 8.2.8
 * textsave�R�}���h�������̃G���g���𓯎��̕ۑ��ł��Ȃ��o�O���C��
   (Thanks: Don, ukiya, xenon)

2008/02/16 Phase 8.2.7
 * insertstr�R�}���h�̓��삪insert�R�}���h�Ɠ����ɂȂ��Ă����o�O���C��
 * entrycount�R�}���h���������G���g��������Ԃ��Ȃ��o�O���C��
   (Thanks: ���΂X)

2008/01/27 Phase 8.2.6
 * gsub�R�}���h���A������pattern��""�Œu������ƁA�u���R����N�����o�O���C��
   (Thanks: C.Ponapalt)

2008/01/26 Phase 8.2.5
 * �������ɔ��p���_(�)������ƈُ퓮����N�����o�O���C��
   (UPX�ɂ��G���o�O�Hgcc�œK����-O1�ɂ��邱�ƂőΉ�)
 * isexist�R�}���h�����[�g�t�H���_�œ��삵�Ȃ��o�O���C��
 * �K����quiet���[�h�ǉ��B�R�}���h���C���I�v�V�����Łu--quiet�v���w�肷��
   ���Ƃɂ��A�������t�@�C����ǂݍ��ނƒ����ɏI������B
 * ninix-aya�p�R���p�C�����̃G���[�C��(Thanks: paulliu)

2005/10/30 Phase 8.2.4
 * rfind�R�}���h�������Ɏ��s������A�d�l�ɂȂ����l��Ԃ��o�O���C���B
   libkawari/kawari_ns.cpp��TEntry::RFind���C���B
 * Visual C++ 7.1�p�ŃR���p�C������ۂ̃v���W�F�N�g�t�@�C����Y�t�B
   (Thanks: �ł�񂳂�)
 * �ؘa����Visual C++ 7.1�ŃR���p�C���ł��Ȃ������C���B
   misc/l10n.cpp��ctow�֐��̎����ߏ����ˑ��������폜�B(Thanks: �ł�񂳂�)
 * ���C�N�t�@�C��(gcc.mak)ninix-aya����������typo���C��(Thanks: jado����)

2005/07/03 Phase 8.2.3
 * �����n�R�}���h�̃C���f�b�N�X�Ǘ��R�[�h�𐮗�
 * inc/dec�̓Y������͈͎w��\�ɋ@�\�g���B�w��͈͂̒P���S��inc/dec����B

2005/06/21 Phase 8.2.3RC (����J)
 * ���Z���Ő��l/�����񎩓����肪�Ԉ���Ă����o�O���C���B
 * �����[�X�Ɏg�p����R���p�C����MinGW 4.1.0(gcc 3.4.2)��
 * �����[�X�̃o�C�i�����Agcc�ɂ�钼��dll�����ɐ؂�ւ�(dllwrap��obsolute?)�B
 * gcc3.x��warning�Ή��B
 * split�̂ʂ��bug��fix.
 * inc/dec�����̓Y�����Ńn���O����bug��fix
 * mktime�R�}���h�ǉ�

2004/09/05 Phase8.2.2
 * Phase 8.2.1�ɂ����āA�����n�R�}���h�̃C���f�b�N�X�ŕ��̒l���g���Ȃ��Ȃ���
   �����o�O���C��

2004/09/04 Phase8.2.1
 * �����n�R�}���h�ɋ��ʂŁA�u�[�v�Ȃǈꕔ�̕������܂ރG���g�����̃C���f�b�N�X
   �w�肪�o���Ȃ��o�O���C��(Thanks 89����@OpenKEEPS�X��)
 * ���ׂ����ninix-aya�����p�b�`�Aphonohawk����̋U�ь�����p�b�`���\�[�X��
   ��荞��(Thanks ���ׂ���Aphonohawk����)

2004/02/01 Phase8.2.0
 * date�R�}���h�ɑ�2������epoc����̌o�ߕb���Ɖ��߂��A���݂̎����Ɠ����悤��
   �t�H�[�}�b�g�o�͂���悤�@�\�ǉ�
 * split�ɑ�3�����Ƃ���""��^�������n���O�A�b�v����o�O���C��
 * split�ɑ�3�����Ƃ���""��^�����ꍇ�Ƒ�3�������ȗ������ꍇ�������ɂȂ�悤
   �@�\�ǉ��B�ǂ�����������Ƃɕ�������
 * split�ɂ��킹�Ajoin����3�����ȗ�����""��^�����ꍇ�Ɠ����ɂȂ�悤�@�\�ǉ�
 * listsub�R�}���h���A���ɏ��������G���g���c���[�\���܂Ō�����o�O���C��
 * �����񌟍�/�u���n�R�}���h�ɂ����āA�}�b�`�p�^�[����""���w�肵���ꍇ�A
   �}�j���A���ʂ�ɑS�Ă̕������E�Ƀ}�b�`����悤�C��
 * �����񌟍�/�u���n�R�}���h�ɂ����āA���݂��Ȃ��C���f�b�N�X���w�肵���ꍇ�A
   �n���O�A�b�v������A�������Ȃ��������ʂ�Ԃ��o�O���C���B���݂��Ȃ�
   �C���f�b�N�X��^�����ꍇ�A���s(""��������-1�A�R�}���h�ˑ�)��Ԃ��B
 * rsub�R�}���h�ǉ�
 * getenv�R�}���h�ǉ�
 * textappend�R�}���h�ǉ�
 * continue �\���R�}���h�ǉ��B���̃R�}���h�̓��[�v�\�����ł̂݋@�\����B
 * ��L�ɍ��킹�Abreak �\���R�}���h�̓��[�v�\�����ł̂݋@�\����悤�ύX

2003/05/18 Phase8.1.0
 * split�̋�v�f�Ɋւ��鈵����Phase7.3.1�̍��ƈقȂ��Ă����o�O��fix
 * �v�f����؂蕶���Ō�������R�}���hjoin�ǉ�
 * �R���p�C���ɗp����UPX�̃o�[�W������1.2.4�ɕύX
 * saorilist�R�}���h�ǉ�
 * "function <�֐���>" �Ŋ֐���`������悤�ɂ���
 * rmfunc �\���R�}���h�ǉ�
 * xargs�̑������ɁA���݂��Ȃ��A�������͋�̃G���g�������w�肷��ƃG���[
   �ɂȂ�o�O��fix
 * shiftcode��shift�Ɠ��������ɂȂ��Ă����o�O��fix(Thanks �ӂ���ƂނX����)
 * �󕶎���Ƃ̃}�b�`��true�ƂȂ�Ȃ����Ƃ��������o�O��fix
 * �ؘa���G���W�������S�I�u�W�F�N�g��(���O�X�g���[���Ȃǂ��܂�)�B����v���Z
   �X���ɕ����C���X�^���X�̐������\�B1�X���b�h/�C���X�^���X�����L��B���
   �U�ь�, ninix�ւ̓K�p��O��B
   �Ȃ��A����ł͕����C���X�^���X�������T�|�[�g����SAORI�����݂��Ȃ��Bnative
   ��SAORI�ɂ��ẮA�B�ꐫ�ۏ؃N���X�ŃK�[�h���Ă���B�ǂ��āA�I�u�W�F�N�g
   SAORI�K�i�̍��肪�K�v�B
 * ����K�i SHIORI OBJECT Interface API(so_*)�̒ǉ�
 * POSIX�v���b�g�t�H�[������SHIORI�C���^�[�t�F�[�X�̍Ē�`�ƁASHIORI-POSIX
   �����e�i���X�̓���
 * Java, Python��SHIORI-Server, SAORI-Client I/F�ɉ��Ή��B��ɋU�ь�Aninix
   �Ή��̒@����B

2002/09/05 Phase8.1.0 beta1 (����J)
 * �����ɂ��reverse�������Ȃ��Ȃ��Ă����o�O��fix
 * �t�@�C��/�f�B���N�g���̑��݊m�F�R�}���h�Qisdir/isexist/isfile�ǉ�
 * date�R�}���h��%s(1970/1/1 00:00:00 UTC����̌o�ߕb��)�ǉ�
 * ���[�U�[�Y�}�j���A���́u!~�v�L�q�~�X��KIS���t�@�����X��date�����s����
   �C���B(Thanks �����邳��)
 * �}�j���A���́u�u���ł��Ȃ��P�[�X�v�Ɂu�W�����Z���̉��Z�q�v�L�ژR���
   �C���B(Thanks �_�C�X����)
 * find�Arfind�����݂��Ȃ��G���g���������������A�K��0��Ԃ��o�O��fix(Thanks
   �Ƃ肠���܂���)
 * SAORI�̑��d���[�h�ȂǂɊւ���΍�(Thanks ��イ����Almm����)

2002/07/05 Phase8.0.0
 * KIS�R�}���h�I�u�W�F�N�g���f�X�g���N�g����Ă��Ȃ������o�O��fix(Thanks
    ���䂳��)
 * �K���N�����ɁA�f�t�H���g��System.DataPath�Ƃ��ăt���p�X��ݒ肷��悤
   �ɂ����B
 * �h�L�������g�ǉ�(�K���ɂ��f�o�b�O�Ȃ�)�A�����B
 * KIS�����Z������v���W�F�N�g�ł�����Project KIU�́A�����̃X�P�W���[��
   ����͑啝�ɒx�ꂽ���̂́A��茻���ɑ������`�ŁA��荂���i����B����
   �����̂ƐM����BProject KIU�́A�{���������ĉ��U�����B
 * �ȍ~�̃����e�i���X�́A�ʏ탂�[�h�ؘ̉a���J���`�[���������e�i�ƂȂ���
   �s����B
 * �������J

2002/06/23 Phase8.0.0 RC3 patch1 (����J)
 * �e�탁�b�Z�[�W�̓��{�ꉻ�A��ӂō�Ɗ��B���Ԃ��ċM�d�B
   ���{�ꉻ���b�Z�[�W���g���ɂ́Arccharset�R�}���h���g���Ă��������B
   ex) rccharset Shift_JIS;

2002/06/22 Phase8.0.0 RC3
 * ���J�����A��������max=list.length()-1���Ă���Ƃ��낪�������B
 * �z��A�N�Z�X�̋t�R���p�C���ŁA$[]�����B����o�O��fix
 * if�̋t�R���p�C����else���]�v�ɓ���o�O��fix
 * clear�ő��݂��Ȃ��P����C���f�b�N�X����Ǝ~�܂�(4G��̃��[�v�����)�o�O
   ��fix(Thanks �݂��Ђ炳��)
 * �F�X�h�L�������g���蒼���B(Thanks �݂��Ђ炳��, 
   ����communicate�̃h�L�������g�o�O��fix(Thanks lmm����)

2002/06/18 Phase8.0.0 RC2 patch2
 * kosui���A�J�����g�f�B���N�g����kawarirc.kis��ǂ܂Ȃ��o�O��fix(Thanks 
   118����@������X�� , �݂��Ђ炳��)
 * ���łɁA�f�t�H���g��DataPath����ɂȂ�o�O��fix
 * ���łɁAkawarirc.kis��ǂ܂Ȃ�����A-norc�I�v�V������ǉ�
 * �G���[���b�Z�[�W�̕���/�܂Ƃߍ�ƊJ�n

2002/06/17 Phase8.0.0 RC2 patch1
 * ���Z����'('�`')'���t�R���p�C������Ȃ��o�O��fix(Thanks ���T����)
 * name, craftmanw�̃��\�[�X�₢���킹�ɑΉ��B�I�[�o�[���C�h�B(Thanks
   �����邳��)

2002/06/15 Phase8.0.0 RC2
 * �r���h�̃V�X�e���𑽏��ύX
 * kosui�̓��{�ꃁ�b�Z�[�W�폜
 * destruct����writeprotect���O��
 * �R���p�C���̖������[�v���܂���ׂ���

2002/06/06 Phase8.0.0 RC1(����J)
 * �P�ꒆ�̋󔒂̈������ȑO�Ɠ����̂��̂ɖ߂��B���ۂ̓���͈ȉ��B
  - �s���s���̋󔒂��폜
  - �G���g����`��':'�╶�f���~�^(','��';')�̒���̋󔒂��폜
  - �P��̖����Ɂu�󔒁{���f���~�^�v������ꍇ�A���̋󔒂��폜

2002/06/02 Phase8.0.0 ��10.1
 * �ȉ��̃o�O/�s����C��
  - shiori.dll�̓��삪�ǂ�ǂ�x���Ȃ�o�O
  - ASSERT_IF_PROTECTED�����O�𐳂����f���Ȃ�(�������̂�Y��Ă���)

2002/05/27 Phase8.0.0 ��10
 * �G���g���������R�}���h find/rfind
 * entry����R�}���h cleartree/listsub/listtree/copy/copytree/move/movetree
 * �ؘa���f�o�b�KON/OFF�R�}���h debugger
 * �����I�Ɋ��S�����s���[�h�����B
       �G���g���� [, �G���g���� ... ] (
          ��, ��,
          ��, ��
       )
   �Ƃ��������B���ʂ��ۂ��B�ۊ��ʂ͕K�{�B���̊ۊ��ʂ́A���̒��ŁA
   ','�ɂ�镶�̃Z�p���[�g���\�ȓ_�Ńu���b�N�Ƃ͈قȂ�B
 * ���Z���Ő^�U�l��"true"/"false"�ŏo�͂���(�d�l�ǂ���)�悤�C��
 * �ȉ��̃o�O/�s����C��
  - ���Z���̌��������Ɋւ����o�O(Thanks �݂��Ђ炳��)
  - DataPath�ݒ�o�O(Thanks ����܂���)
  - SecurityLevel�ݒ�(����Ȃ�)�o�O
  - readdir�̌��ʊi�[�o�O(Thanks ���䂳��)
  - substr�̈�������o�O
  - SAORI-Client�ɂ�GET Version���Ƀv���g�R�������t���Ȃ��o�O(Thanks ����������@���X�X��)
  - ���O�ݒ�𖳎����ďo�͂��镔��
  - �l�X�ȃh�L�������g�o�O(keeps8�̃g�[�N���܂�)
 * ����т��ƍ�����

2002/05/04 Phase8.0.0 ��9.1
 * �G���g���z��Ăяo���ŁA���̒l��F�����Ă��Ȃ������B
 * Direct SSTP�ɂ��Akdb(���ǂ�)�����B�󂯑��ɃX�N���v�g���K�v�B

2002/05/02 Phase8.0.0 ��9
 * �R���p�C���̖������[�v�o�O��fix. �̒������o��������񂾂��ǂȁ[�B
 * kis_reference.html�B���ɏI�������[�I
 * �����J�J�n

2002/05/01 Phase8.0.0 ��8.2(����J)
 * compare
 * textload/readdir�̈����̏��Ԃ�ύX
 * version,craftman,shioriid�̃I�[�o�[���C�h������
 * ���݂��Ȃ��G���g���ɑ΂��郊�[�h�A�N�Z�X�Ń��O��f���P�[�X�����p��Ɍ���B
   loglevel decl���݁B

2002/04/28 Phase8.0.0 ��8.1(����J)
 * wordcount, entrycount
 * ���C�Z���X��芮�S�����B����ƌ��J�ł���B

2002/04/27 Phase8.0.0 ��8
 * System.Resource.����邱�Ƃ͖��Ӗ��Ȃ̂ŁA2.5���\�[�X�擾��@��
   System.Callback.OnResource�ɕύX.
 * foreach���o�O���Ă����I
 * string�nKIS�ŕ��̃C���f�b�N�X��F��
 * substr�̑�O�����̉��߂𕔕�������̒����ɕύX.
 * writeprotect�R�}���h�ǉ�
 * Logger�኱�C��
 * ���݂��Ȃ��G���g�����Ăяo�������Ƀ��O

2002/04/26 Phase8.0.0 ��7.1
 * ������̋t�R���p�C���o�O
 * match_at��SJIS���
 * cncpath���̑���SJIS���

2002/04/25 Phase8.0.0 ��7
 * mingw�łɍ����ւ�
 * getrandom���o�^����Ă��Ȃ�����(-_-;
 * garbage collector
 * KIS_logfile�̖��������|�C���^�ɂ�郊���[�h������fix.

2002/04/24 Phase8.0.0 ��6
 * programming.html
 * ���\�[�X�R���p�C���Ɏ��s���Ă����̂ŁA�ꎞ�I�Ɏ��O���B

2002/04/23 Phase8.0.0 ��5
 * programming.html�D����
 * ���Ɓ[���̃h�L�������g����
 * �h�L�������g���܂��܎蒼��
 * �x�A����������[�h�����B����B
 * ����test, expr�R�}���h���폜�Bdll���Ă�300KB��؂����B

2002/04/22 Phase8.0.0 ��4
 * securitylevel �w��R�}���h
 * insert, match_at
 * erase�͕K�v�Ȃ������Bclear���������B
 * MT BSD���C�Z���X��
 * randomseed���� -> srand
 * start.html
 * license���Ή������BMT���C�Z���X�\�L�܂Ŋ܂߂����C�Z���X���́A
   ver license;�ŏo�́B�����ʓ|�c
 * license.html

2002/04/19 Phase8.0.0 ��3
 * �G���g������ǂޕ����̕��@�Ǝ������኱�C���B
   ����$$entry[0][1]�Ƃ��ł���悤�Ɂc�c
 * callsaori�ŗ����錏�B����bcc�̃o�O�B
 * SHIORI/3.0�Ή�
 * Log�@�\�A�āX�x����
 * BNF�C���Ƃ���ɍ��킹���R���p�C���̕ύX�B
 * index.html

2002/04/17 Phase8.0.0 ��2
 * SAORI Client
 * Log�@�\�A�ēx����

2002/04/15 Phase8.0.0 ��1
 * �V�C���^�v���^��Phase7.9.0���}�[�W�B

---
#Future

##8.2(??)
 * i18n patch (Thanks whoami)

##9.0(???)
 * boost regex
 * rexpr
 ? lambda
 ? SAORI/2.0
 ? namespace