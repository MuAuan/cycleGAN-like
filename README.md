# cycleGAN-like
cycleGAN-like makes better fittings by the followings

    A ⇒ G(Dx) ⇒ B ⇒ F(Dy)　⇒ A'
The same Generator & Discriminator are used in this program

    G∗,F∗ = argmin max L(G,F,Dx,Dy ).
             G,F Dx,Dy
    F=G, Dx=Dy
    F*=G*
Therfore,
    A ⇒ Generator(pix2pix(encoder-decoder_type)) ⇒ B ⇒ Generator(pix2pix(encoder-decoder_type))　⇒ A'

