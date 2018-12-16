************
Introduction
************

.. contents:: Table of Contents

.. written begin

In the literature, there are two main types of electromagnetic launcher. The main difference of these types that supply current is *direct connected* to armature (**railgun**) or *induced* in the armature (**coilgun**). For the railguns the armature and stator current, relative position and velocity of each other are independent. For the coilguns hte induced armature current is a fuction of the stator current and its position and velocity :cite:`engel:2017`. Other kinds of launchers and **classifications** can be found in the literature :cite:`weldon:1989` :cite:`engel:2017`. In this work, induction type electromagnetics launchers are investigated. 

Electromagnetic induction launchers or accelerators have been called with different names in the literature: coaxial, tubular induction, magnetic or in a more inclusive manner coilgun.

History
=======

The basic physics of magnetic accelerators, in other words electromagnetic launchers (EML) has been well understood since Maxwell's time late in 19th century. Then, rotary magnetic motors such as the common induction motors have been more popular for decades. However, EMLs have not received the same attention. It is only in the 1970s that they have been seriously investigated. By these years it has had two major difficulties. First, the windings of all motors were wound around a ferromagnetic material such as iron and alloys. But, EMLs must operate above 10 tesla that iron and its alloys will saturate in this region. In addition, iron-free construction was very difficult because of the presence of extreme structural forces. Second, the extremely high electrical power input needed makes it difficult to operate. For instance, the acceleration energy of over 10 MJ must be stored and then delivered in less than a millisecond :cite:`mongeau:1982`.

A theoretical and experimental investigation of coaxial air core launchers that were driven by capacitor bank was performed by Mongeau in his thesis. Experimental test was done by a helical railgun and discrete coil launchers  :cite:`mongeau:1982`.

.. written end

.. Railgun ile coilgun arasındaki yarış ve popülerite

Railgun vs Coilgun
==================

The current interest in electromagnetic acceleration of masses has resulted in something of a competition between the railguns and coaxial accelerators. If proliferation is any measure of success, railguns presently appear to be leading the competition. Actually, there are several fundamental reasons why the railguns are enjoying their present surge of popularity which in no way reflects inherent superiority over the induction launchers for all applications :cite:`driga:1986`.

.. Railgun basit olduğu için ilk olarak o geliştirilmiştir ve kolayca üretilebilir
.. Railgun ın inductance gradient i boyuttan bağımsızdır ancak coilgun da değişir bu yüzden küçük boyutlarda iyi performanslı coilgun üretmek zordur.

Railguns are the simplest of the electromagnetic launchers and it is natural that they should be developed first. They undoubtedly benefit from the fact that virtually anyone with access to a laboratory or shop can quickly fabricate a small railgun which will accelerate a projectile. This advantage of simplicity is compounded by the scaling relationships for the two concepts. Whereas the inductance gradient of the railgun is essentially independent of scale, the comparable gradient for induction launchers is quite sensitive to it, improving dramatically in larger accelerators. Thus, it is quite difficult to build a small-scale coaxial launcher with impressive performance :cite:`driga:1986`.

.. Railgun farklı uygulamalar için geliştirilmiş darbe homopolar güç kaynağını bir anahtar yardımıyla kullanabilir. 
.. İndüksiyon fırlatıcılar ise bu bakış açısı ile varolan güç kaynaklarını kullanabilmek için üzerinde çalışılmaktadır.

Moreover, the railgun has had the benefit of the existence of the pulsed homopolar generator in conjunction with an inductor and an opening switch, an inherently compatible power supply, that had been developed for other programs. The induction launchers enjoyed no such serendipitous benefit and have suffered as a result. In fact, much of the effort expended on the development of coaxial accelerators to date, when viewed in this light, appears to have been directed toward forcing the accelerator to conform to existing power supplied :cite:`driga:1986`.

Potential benefits of coilgun:

- Increased efficiency
- Greater freedom of projectile design
- Elimination of switching and synchronization requirements

Among so many variants, few have merit as simple and efficient accelerators. We will limit ourselves to the double sided induction accelerator, and the tubular accelerator :cite:`driga:1986`.

Only the tubular induction accelerator has the circular symmetry implied by the term coaxial as shown in :numref:`tubular-induction-accelerator` :cite:`driga:1986`.

.. figure:: ../img/tubular-induction-accelerator.png
    :align: center
    :scale: 100 %
    :name: tubular-induction-accelerator

    : Tubular induction accelerator.

From the theory of the conventional rotating induction motors it is known that their energy efficiency for starting operation expressed in energy terms is less than 50%. For each unit of energy stored kinetically in the rotor, a greater amount is dissipated in the Joule heating of the rotor by slip losses :cite:`driga:1986`.

In exactly the same manner[4], a projectile accelerated from rest by a constant speed traveling field will be subject to the same slip losses, which amount to :math:`W_{PJ}`, for the entire launch period. Actually the projectile does not reach the speed of traveling field and the energy loss is (:numref:`single-stage-acceleration`) :cite:`driga:1986`

.. math::
    :label: W_pj

    W_{PJ} = \int_0^{v_{TF}} m_p (v_{TF}-v) dv = m_p (v_{TF} v_m - \frac{v_m^2}{2})

where :math:`m_p` is the projectile mass [kg], :math:`v_{TF}` is the speed of travelling field [m/s], :math:`v` is the instantaneous speed of projectile [m/s] and :math:`v_m` is the projectile output velocity (at the muzzle of the launcher).

.. figure:: ../img/single-stage-acceleration.png
    :align: center
    :scale: 100 %
    :name: single-stage-acceleration

    : Single-stage acceleration.

For a two stage system (:numref:`two-stage-acceleration`) comprising two traveling field speeds, the energy loss decreases considerably :cite:`driga:1986`.

.. figure:: ../img/two-stage-acceleration.png
    :align: center
    :scale: 100 %
    :name: two-stage-acceleration

    : Two-stage acceleration.

.. Birden fazla bölümden oluşan fırlatıcının daha verimli olduğundan bahsediyor.

The number of stages can be further increased which would considerably increase the energy efficiency and reduce to a minimum the Joule loss in the projectile. At the limit this corresponds to a continuous increase in the pole pitch or a continuous change in the frequency of the currents producing the traveling field (Fig 3 c ) :cite:`driga:1986`.

The variable pitch winding, which sometimes is called a graded winding, is fabricated by increasing the coil spacings - thus increasing the traveling field velocity towards the end of the launcher – for the tubular construction :cite:`driga:1986`.

.. RFG anlatılmış

The second manner to obtain an accelerated field is to continuously vary the supply frequency. This way, as the armature is accelerated down an essentially constant pitch stator winding, the driving frequency increases with the armature velocity. Of course, this is just the opposite of. what happens in an alternator or compulsator, as energy is extracted. Additionally, as the speed voltage of the accelerator rises, it is desirable for the voltage of the generator to rise as well :cite:`driga:1986`.

A CEM concept called the "rising frequency generator" (RFG) [6] is proposed to meet the power supply requirements of ,the coaxial accelerator. This device can utilize the electrical generating configuration of an alternator, low impedance alternator, or compulsator -- single or multiphase. It consists of a rotor and a stator having a moment of inertia many times higher than the rotor (a naturally occurring situation which can be tailored by design) both of which are initially rotating in the same direction, the stator rotational speed being somewhat higher. The electrical frequency of the output, of course, is a function of the differential speed, omega_s-omega_r, as is the generated voltage. As power is generated, equal and opposite torques will be applied to the rotor and stator, and the rotor will change speed faster (slow down) due to its lower inertia. As the rotor slows, the differential between rotor and stator speed increases, increasing frequency and output voltage and achieving the desired effect :cite:`driga:1986`. 

A variant of this RFG concept involves using a stationary stator with a rotating magnetic field produced by a multiphase AC excitation current.

By matching the generator voltage, frequency, rotor and stator inertias, and initial velocities to the requirements of the coaxial accelerator, an integrated power supply/accelerator system can be designed. An important part of this integration is done by mounting the pulse generator excitation source (i.e., homopolar generator) on the same shaft as the pulse generator thus forming a "cascade" of electrical machines essential to obtaining the proper, electromechanical energy conversion :cite:`driga:1986`.
