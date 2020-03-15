//---------------------------------------------------------------------------

#include <vcl.h>
#pragma hdrstop

#include "Unit1.h"
//---------------------------------------------------------------------------
#pragma package(smart_init)
#pragma resource "*.dfm"
TForm1 *Form1;
int Mermi=11;
//---------------------------------------------------------------------------
__fastcall TForm1::TForm1(TComponent* Owner)
        : TForm(Owner)
{
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image1Click(TObject *Sender)
{
    Mermi--;
    Image2->Picture->LoadFromFile(IntToStr(Mermi)+".bmp");
}
//---------------------------------------------------------------------------
