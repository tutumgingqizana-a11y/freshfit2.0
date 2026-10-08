import { Target, Heart, Users, TrendingDown, ArrowRight, Leaf } from 'lucide-react';

type AboutPageProps = {
  onNavigate: (page: 'products' | 'contact' | 'auth') => void;
};

export default function AboutPage({ onNavigate }: AboutPageProps) {
  const values = [
    { icon: Heart, title: 'Accessibility', text: 'Fitness should be for everyone. We keep prices low so cost is never a barrier to staying healthy.' },
    { icon: Target, title: 'Quality', text: 'Every product is tested and chosen for durability. Affordable does not mean cheap — it means smart value.' },
    { icon: Users, title: 'Community', text: 'We are building a community of beginners and home-workout enthusiasts who support each other.' },
    { icon: TrendingDown, title: 'Simplicity', text: 'No complicated equipment or gimmicks. Just the essentials you need to build a consistent routine.' },
  ];

  return (
    <div className="pt-16 lg:pt-20">
      {/* Hero */}
      <section className="relative py-16 lg:py-24 bg-gradient-to-br from-emerald-50 via-teal-50 to-white overflow-hidden">
        <div className="absolute top-10 right-10 w-80 h-80 bg-emerald-200/20 rounded-full blur-3xl" />
        <div className="relative max-w-5xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
          <div className="inline-flex items-center gap-2 px-4 py-1.5 bg-emerald-100 text-emerald-700 rounded-full text-sm font-medium mb-6">
            <Leaf className="w-4 h-4" />
            About FreshFit
          </div>
          <h1 className="text-3xl lg:text-5xl font-bold text-gray-900 leading-tight mb-6">
            Making fitness accessible, <span className="text-emerald-600">one product at a time</span>
          </h1>
          <p className="text-lg lg:text-xl text-gray-600 leading-relaxed max-w-3xl mx-auto">
            FreshFit was born from a simple idea: everyone deserves to feel healthy and strong, regardless of their budget. We provide affordable, high-quality fitness products that make working out at home easy and enjoyable.
          </p>
        </div>
      </section>

      {/* Problem & Solution */}
      <section className="py-16 lg:py-24 bg-white">
        <div className="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
          <div className="grid lg:grid-cols-2 gap-8 lg:gap-12">
            <div className="p-8 lg:p-10 rounded-3xl bg-red-50 border border-red-100">
              <div className="w-14 h-14 rounded-2xl bg-red-100 flex items-center justify-center mb-6">
                <TrendingDown className="w-7 h-7 text-red-500" />
              </div>
              <h2 className="text-2xl font-bold text-gray-900 mb-4">The Problem</h2>
              <p className="text-gray-600 leading-relaxed mb-4">
                Many people want to exercise and live healthier lives, but fitness equipment can be expensive and difficult to access. Gym memberships are a recurring cost that not everyone can afford — especially students and young professionals.
              </p>
              <p className="text-gray-600 leading-relaxed">
                The result? People who want to start their fitness journey are held back before they even begin.
              </p>
            </div>

            <div className="p-8 lg:p-10 rounded-3xl bg-emerald-50 border border-emerald-100">
              <div className="w-14 h-14 rounded-2xl bg-emerald-100 flex items-center justify-center mb-6">
                <Heart className="w-7 h-7 text-emerald-600 fill-emerald-600" />
              </div>
              <h2 className="text-2xl font-bold text-gray-900 mb-4">Our Solution</h2>
              <p className="text-gray-600 leading-relaxed mb-4">
                FreshFit provides affordable, easy-to-use workout products that let you exercise at home, at your own pace. No expensive gym membership, no complicated equipment — just quality fitness gear at prices that make sense.
              </p>
              <p className="text-gray-600 leading-relaxed">
                From resistance bands to yoga mats, we have everything you need to build a sustainable home workout routine.
              </p>
            </div>
          </div>
        </div>
      </section>

      {/* Values */}
      <section className="py-16 lg:py-24 bg-gray-50">
        <div className="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
          <div className="text-center mb-12">
            <h2 className="text-3xl lg:text-4xl font-bold text-gray-900 mb-3">What We Stand For</h2>
            <p className="text-gray-500 text-lg">The values that guide everything we do</p>
          </div>
          <div className="grid sm:grid-cols-2 lg:grid-cols-4 gap-6">
            {values.map((value, i) => (
              <div key={i} className="bg-white p-6 lg:p-8 rounded-2xl shadow-sm hover:shadow-lg transition-shadow">
                <div className="w-12 h-12 rounded-xl bg-emerald-50 flex items-center justify-center mb-5">
                  <value.icon className="w-6 h-6 text-emerald-600" />
                </div>
                <h3 className="font-bold text-gray-900 text-lg mb-2">{value.title}</h3>
                <p className="text-gray-500 text-sm leading-relaxed">{value.text}</p>
              </div>
            ))}
          </div>
        </div>
      </section>

      {/* Customer Persona */}
      <section className="py-16 lg:py-24 bg-white">
        <div className="max-w-5xl mx-auto px-4 sm:px-6 lg:px-8">
          <div className="grid lg:grid-cols-2 gap-8 lg:gap-12 items-center">
            <div className="relative">
              <div className="rounded-3xl overflow-hidden shadow-xl aspect-square">
                <img
                  src="https://images.pexels.com/photos/6453430/pexels-photo-6453430.jpeg?auto=compress&cs=tinysrgb&h=650&w=940"
                  alt="Young woman doing yoga at home on a FreshFit yoga mat, demonstrating affordable home fitness"
                  className="w-full h-full object-cover"
                />
              </div>
            </div>
            <div>
              <h2 className="text-2xl lg:text-3xl font-bold text-gray-900 mb-4">Who We Serve</h2>
              <p className="text-gray-600 leading-relaxed mb-6">
                FreshFit is built for young adults aged 18-35 — students, working professionals, and anyone who prefers working out at home. People like Lihle.
              </p>
              <div className="bg-gray-50 rounded-2xl p-6 space-y-3">
                <div className="flex items-center gap-3">
                  <div className="w-12 h-12 rounded-full bg-emerald-600 flex items-center justify-center text-white font-bold text-lg flex-shrink-0">
                    L
                  </div>
                  <div>
                    <p className="font-semibold text-gray-900">Lihle, 24</p>
                    <p className="text-sm text-gray-500">Student in Cape Town</p>
                  </div>
                </div>
                <div className="pt-3 border-t border-gray-200 space-y-2 text-sm">
                  <p><span className="font-medium text-gray-700">Needs:</span> <span className="text-gray-600">Affordable workout equipment for home use</span></p>
                  <p><span className="font-medium text-gray-700">Challenge:</span> <span className="text-gray-600">Cannot afford an expensive gym membership or equipment</span></p>
                  <p><span className="font-medium text-gray-700">Goal:</span> <span className="text-gray-600">Stay active and healthy on a student budget</span></p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>

      {/* CTA */}
      <section className="py-16 lg:py-20 bg-gradient-to-r from-emerald-600 to-teal-600">
        <div className="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
          <h2 className="text-2xl lg:text-3xl font-bold text-white mb-4">Join the FreshFit Community</h2>
          <p className="text-emerald-50 text-lg mb-8">Start your fitness journey today with affordable, quality products.</p>
          <div className="flex flex-col sm:flex-row gap-4 justify-center">
            <button onClick={() => onNavigate('products')} className="px-8 py-4 bg-white text-emerald-700 font-semibold rounded-xl hover:scale-105 active:scale-95 transition-all shadow-lg flex items-center justify-center gap-2 group">
              Shop Products
              <ArrowRight className="w-5 h-5 group-hover:translate-x-1 transition-transform" />
            </button>
            <button onClick={() => onNavigate('auth')} className="px-8 py-4 bg-white/20 text-white font-semibold rounded-xl hover:bg-white/30 transition-colors border border-white/30">
              Sign Up
            </button>
            <button onClick={() => onNavigate('contact')} className="px-8 py-4 bg-emerald-700/50 text-white font-semibold rounded-xl hover:bg-emerald-700/70 transition-colors border border-white/20">
              Contact Us
            </button>
          </div>
        </div>
      </section>
    </div>
  );
}
